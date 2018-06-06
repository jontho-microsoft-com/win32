---
Description: Creates a digital signature on previously signed content.
ms.assetid: c0a3de75-afba-45ba-b701-2729f4495eda
title: SignedData.CoSign method
ms.technology: desktop
ms.prod: windows
ms.author: windowssdkdev
ms.topic: article
ms.date: 05/31/2018
---

# SignedData.CoSign method

\[The **CoSign** method is available for use in the operating systems specified in the Requirements section. Instead, use the [**SignedCms Class**](https://www.bing.com/search?q=**SignedCms+Class**) in the [**System.Security.Cryptography.Pkcs**](https://www.bing.com/search?q=**System.Security.Cryptography.Pkcs**) namespace.\]

The **CoSign** method creates a [*digital signature*](https://msdn.microsoft.com/d007cbb9-b547-4dc7-bc22-b526f650f7c2) on previously signed content.

## Syntax


```VB
SignedData.CoSign( _
  [ ByVal Signer ], _
  [ ByVal EncodingType ] _
)
```



## Parameters

<dl> <dt>

*Signer* \[in, optional\]
</dt> <dd>

A reference to the [**Signer**](signer.md) object of the signer of the data. The **Signer** object must have access to the private key of the certificate used to sign. This parameter can be **NULL**; for more information, see Remarks.

</dd> <dt>

*EncodingType* \[in, optional\]
</dt> <dd>

A value of the [**CAPICOM\_ENCODING\_TYPE**](capicom-encoding-type.md) enumeration that indicates how the signed data is to be encoded. The default value is CAPICOM\_ENCODE\_BASE64. This parameter can be one of the following values.



| Value                                                                                                                                                                                  | Meaning                                                                                                                                                                                                                            |
|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| <span id="CAPICOM_ENCODE_ANY"></span><span id="capicom_encode_any"></span><dl> <dt>**CAPICOM\_ENCODE\_ANY**</dt> </dl>          | This encoding type is used only when the input data has an unknown encoding type. If this value is used to specify the output's encoding type, CAPICOM\_ENCODE\_BASE64 will be used instead. Introduced in CAPICOM 2.0.<br/> |
| <span id="CAPICOM_ENCODE_BASE64"></span><span id="capicom_encode_base64"></span><dl> <dt>**CAPICOM\_ENCODE\_BASE64**</dt> </dl> | Data is saved as a base64-encoded string.<br/>                                                                                                                                                                               |
| <span id="CAPICOM_ENCODE_BINARY"></span><span id="capicom_encode_binary"></span><dl> <dt>**CAPICOM\_ENCODE\_BINARY**</dt> </dl> | Data is saved as a pure binary sequence.<br/>                                                                                                                                                                                |



 

</dd> </dl>

## Return value

This method returns a string that contains the encoded, signed data.

If this method fails, an error will be thrown. The **Err** object will contain additional information about the error.

## Remarks

> \[!Important\]  
> When this method is called from a web script, the script needs to use your [*private key*](https://msdn.microsoft.com/2fe6cfd3-8a2e-4dbe-9fb8-332633daa97a) to create a digital signature. Allowing untrusted websites to use your private key is a security risk. A dialog box that asks whether the website can use your private key appears when this method is first called. If you allow the script to use your private key to create a digital signature and select "Do not show this dialog box again," the dialog box will no longer appear for any script within that domain that uses your private key to create a digital signature. However, scripts outside that domain that attempt to use your private key to create a digital signature will still cause this dialog box to appear. If you do not allow the script to use your private key and select "Do not show this dialog box again," scripts within that domain will automatically be refused the ability to use your private key to create digital signatures.

 

Cosigners are not guaranteed to be in any particular order.

The following results apply to the *Signer* parameter value:

-   If the *Signer* parameter is not **NULL**, this method uses the private key pointed to by the associated certificate to encrypt the cosignature. If the private key pointed to by the certificate is not available, the method fails.
-   If the *Signer* parameter is **NULL** and there is exactly one certificate in the CURRENT\_USER MY store that has access to a private key, that certificate is used to create the cosignature.
-   If the *Signer* parameter is **NULL**, the [**Settings.EnablePromptForCertificateUI**](settings-enablepromptforcertificateui.md) property value is true, and there is more than one certificate in the CURRENT\_USER MY store with an available private key, a dialog box appears that allows the user to select which certificate is used.
-   If the *Signer* parameter is **NULL** and the [**Settings.EnablePromptForCertificateUI**](settings-enablepromptforcertificateui.md) property is false, the method fails.
-   If the *Signer* parameter is **NULL** and there is no certificate in the CURRENT\_USER MY store with an available private key, the method fails.

## Requirements



|                            |                                                                                        |
|----------------------------|----------------------------------------------------------------------------------------|
| Redistributable<br/> | CAPICOM 2.0 or later on Windows Server 2003 and Windows XP<br/>                  |
| DLL<br/>             | <dl> <dt>Capicom.dll</dt> </dl> |



## See also

<dl> <dt>

[**Cryptography Objects**](cryptography-objects.md)
</dt> <dt>

[**SignedData**](signeddata.md)
</dt> </dl>

 

 



