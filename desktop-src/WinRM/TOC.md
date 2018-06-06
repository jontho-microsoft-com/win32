# [Windows Remote Management](portal.md)
## [About Windows Remote Management](about-windows-remote-management.md)
### [What's New in WinRM 2.0](whats-new-in-winrm.md)
### [Installation and Configuration for Windows Remote Management](installation-and-configuration-for-windows-remote-management.md)
### [Windows Remote Management Architecture](windows-remote-management-architecture.md)
### [WS-Management Protocol](ws-management-protocol.md)
### [Scripting in Windows Remote Management](scripting-in-windows-remote-management.md)
### [Authentication for Remote Connections](authentication-for-remote-connections.md)
### [Proxy Servers and WinRM](proxy-servers-and-winrm.md)
### [Windows Remote Management and WMI](windows-remote-management-and-wmi.md)
### [DMTF Profile Discovery Through Association Traversal](dmtf-association-traversal.md)
### [Infrastructure for Managing Hosted Services](winrm-application-hosting.md)
### [IIS Host Plug-in Configuration](iis-host-plug-in-configuration.md)
### [WinRM Service Plug-in Configuration](wsman-service-plug-in-configuration.md)
### [Remote Shell Infrastructure Improvements](remote-shell-infrastructure-improvements.md)
#### [Multi-Hop Support in WinRM](multi-hop-support.md)
#### [Quota Management for Remote Shells](quotas.md)
### [Resource URIs](resource-uris.md)
#### [URI Prefixes](uri-prefixes.md)
### [Remote Hardware Management](remote-hardware-management.md)
### [Events](events.md)
## [Using Windows Remote Management](using-windows-remote-management.md)
### [WinRM Best Practices](winrm-best-practices.md)
### [Detecting Whether a Remote Computer Supports WS-Management Protocol](detecting-whether-a-remote-computer-supports-ws-management-protocol.md)
### [Obtaining Data from the Local Computer](obtaining-data-from-the-local-computer.md)
### [Obtaining Data from a Remote Computer](obtaining-data-from-a-remote-computer.md)
### [Enumerating or Listing All Instances of a Resource](enumerating-or-listing-all-instances-of-a-resource.md)
### [Querying for Specific Instances of a Resource](querying-for-specific-instances-of-a-resource.md)
### [Displaying XML Output from WinRM Scripts](displaying-xml-output-from-winrm-scripts.md)
## [Windows Remote Management Reference](windows-remote-management-reference.md)
### [WinRM Client Shell API](client-shell-api.md)
#### [Client Shell API Additional Functions](client-shell-api-additional-functions.md)
##### [WSManGetErrorMessage](/windows/desktop/api/Wsman/nf-wsman-wsmangeterrormessage)
##### [WSManGetSessionOptionAsDword](/windows/desktop/api/Wsman/nf-wsman-wsmangetsessionoptionasdword)
##### [WSManGetSessionOptionAsString](/windows/desktop/api/Wsman/nf-wsman-wsmangetsessionoptionasstring)
##### [WSManSetSessionOption](/windows/desktop/api/Wsman/nf-wsman-wsmansetsessionoption)
#### [Client Shell API Core Functions](client-shell-api-core-functions.md)
##### [WSManCloseCommand](/windows/desktop/api/Wsman/nf-wsman-wsmanclosecommand)
##### [WSManCloseOperation](/windows/desktop/api/Wsman/nf-wsman-wsmancloseoperation)
##### [WSManCloseSession](/windows/desktop/api/Wsman/nf-wsman-wsmanclosesession)
##### [WSManCloseShell](/windows/desktop/api/Wsman/nf-wsman-wsmancloseshell)
##### [WSManConnectShell](/windows/desktop/api/Wsman/nf-wsman-wsmanconnectshell)
##### [WSManConnectShellCommand](/windows/desktop/api/Wsman/nf-wsman-wsmanconnectshellcommand)
##### [WSManCreateSession](/windows/desktop/api/Wsman/nf-wsman-wsmancreatesession)
##### [WSManCreateShell](/windows/desktop/api/Wsman/nf-wsman-wsmancreateshell)
##### [WSManCreateShellEx](/windows/desktop/api/Wsman/nf-wsman-wsmancreateshellex)
##### [WSManDeinitialize](/windows/desktop/api/Wsman/nf-wsman-wsmandeinitialize)
##### [WSManDisconnectShell](/windows/desktop/api/Wsman/nf-wsman-wsmandisconnectshell)
##### [WSManInitialize](/windows/desktop/api/Wsman/nf-wsman-wsmaninitialize)
##### [WSManReceiveShellOutput](/windows/desktop/api/Wsman/nf-wsman-wsmanreceiveshelloutput)
##### [WSManReconnectShell](/windows/desktop/api/Wsman/nf-wsman-wsmanreconnectshell)
##### [WSManReconnectShellCommand](/windows/desktop/api/Wsman/nf-wsman-wsmanreconnectshellcommand)
##### [WSManRunShellCommand](/windows/desktop/api/Wsman/nf-wsman-wsmanrunshellcommand)
##### [WSManRunShellCommandEx](/windows/desktop/api/Wsman/nf-wsman-wsmanrunshellcommandex)
##### [WSManSendShellInput](/windows/desktop/api/Wsman/nf-wsman-wsmansendshellinput)
##### [WSManSignalShell](/windows/desktop/api/Wsman/nf-wsman-wsmansignalshell)
#### [Client Shell API Enumerations](client-shell-api-enumerations.md)
##### [WSManAuthenticationFlags](/windows/desktop/api/Wsman/ne-wsman-wsmanauthenticationflags)
##### [WSManCallbackFlags](/windows/desktop/api/Wsman/ne-wsman-wsmancallbackflags)
##### [WSManDataType](/windows/desktop/api/Wsman/ne-wsman-wsmandatatype)
##### [WSManProxyAccessType](/windows/desktop/api/Wsman/ne-wsman-wsmanproxyaccesstype)
##### [WSManSessionOption](/windows/desktop/api/Wsman/ne-wsman-wsmansessionoption)
#### [Client Shell API Structures and Definitions](client-shell-api-structures.md)
##### [WSMAN_AUTHENTICATION_CREDENTIALS](/windows/desktop/api/Wsman/ns-wsman-_wsman_authentication_credentials)
##### [WSMAN_DATA](/windows/desktop/api/Wsman/ns-wsman-_wsman_data)
##### [WSMAN_DATA_BINARY](/windows/desktop/api/Wsman/ns-wsman-_wsman_data_binary)
##### [WSMAN_DATA_TEXT](/windows/desktop/api/Wsman/ns-wsman-_wsman_data_text)
##### [WSMAN_ENVIRONMENT_VARIABLE](/windows/desktop/api/Wsman/ns-wsman-_wsman_environment_variable)
##### [WSMAN_ENVIRONMENT_VARIABLE_SET](/windows/desktop/api/Wsman/ns-wsman-_wsman_environment_variable_set)
##### [WSMAN_ERROR](/windows/desktop/api/Wsman/ns-wsman-_wsman_error)
##### [WSMAN_KEY](/windows/desktop/api/Wsman/ns-wsman-_wsman_key)
##### [WSMAN_OPTION](/windows/desktop/api/Wsman/ns-wsman-_wsman_option)
##### [WSMAN_OPTION_SET](/windows/desktop/api/Wsman/ns-wsman-_wsman_option_set)
##### [WSMAN_PROXY_INFO](/windows/desktop/api/Wsman/ns-wsman-_wsman_proxy_info)
##### [WSMAN_RECEIVE_DATA_RESULT](/windows/desktop/api/Wsman/ns-wsman-_wsman_receive_data_result)
##### [WSMAN_RESPONSE_DATA](/windows/desktop/api/Wsman/ns-wsman-_wsman_response_data)
##### [WSMAN_SELECTOR_SET](/windows/desktop/api/Wsman/ns-wsman-_wsman_selector_set)
##### [WSMAN_SHELL_ASYNC](/windows/desktop/api/Wsman/ns-wsman-_wsman_shell_async)
##### [WSMAN_SHELL_COMPLETION_FUNCTION](/windows/desktop/api/Wsman/nc-wsman-wsman_shell_completion_function)
##### [WSMAN_SHELL_DISCONNECT_INFO](/windows/desktop/api/Wsman/ns-wsman-_wsman_shell_disconnect_info)
##### [WSMAN_SHELL_STARTUP_INFO](/windows/desktop/api/Wsman/ns-wsman-_wsman_shell_startup_info_v10)
##### [WSMAN_STREAM_ID_SET](/windows/desktop/api/Wsman/ns-wsman-_wsman_stream_id_set)
##### [WSMAN_USERNAME_PASSWORD_CREDS](/windows/desktop/api/Wsman/ns-wsman-_wsman_username_password_creds)
### [WinRM Plug-in API](winrm-plugin-api.md)
#### [Authorization Plug-in Entry Points](authorization-plug-in-entry-points.md)
##### [WSMAN_PLUGIN_AUTHORIZE_OPERATION](/windows/desktop/api/Wsman/nc-wsman-wsman_plugin_authorize_operation)
##### [WSMAN_PLUGIN_AUTHORIZE_QUERY_QUOTA](/windows/desktop/api/Wsman/nc-wsman-wsman_plugin_authorize_query_quota)
##### [WSMAN_PLUGIN_AUTHORIZE_RELEASE_CONTEXT](/windows/desktop/api/Wsman/nc-wsman-wsman_plugin_authorize_release_context)
##### [WSMAN_PLUGIN_AUTHORIZE_USER](/windows/desktop/api/Wsman/nc-wsman-wsman_plugin_authorize_user)
#### [Authorization Plug-in Methods](authorization-plug-in-methods.md)
##### [WSManPluginAuthzOperationComplete](/windows/desktop/api/Wsman/nf-wsman-wsmanpluginauthzoperationcomplete)
##### [WSManPluginAuthzQueryQuotaComplete](/windows/desktop/api/Wsman/nf-wsman-wsmanpluginauthzqueryquotacomplete)
##### [WSManPluginAuthzUserComplete](/windows/desktop/api/Wsman/nf-wsman-wsmanpluginauthzusercomplete)
#### [Operations Plug-in Entry Points](operations-plug-in-entry-points.md)
##### [WSMAN_PLUGIN_COMMAND](/windows/desktop/api/Wsman/nc-wsman-wsman_plugin_command)
##### [WSMAN_PLUGIN_CONNECT](/windows/desktop/api/WsMan/nc-wsman-wsman_plugin_connect)
##### [WSMAN_PLUGIN_RECEIVE](/windows/desktop/api/Wsman/nc-wsman-wsman_plugin_receive)
##### [WSMAN_PLUGIN_RELEASE_COMMAND_CONTEXT](/windows/desktop/api/Wsman/nc-wsman-wsman_plugin_release_command_context)
##### [WSMAN_PLUGIN_RELEASE_SHELL_CONTEXT](/windows/desktop/api/Wsman/nc-wsman-wsman_plugin_release_shell_context)
##### [WSMAN_PLUGIN_SEND](/windows/desktop/api/Wsman/nc-wsman-wsman_plugin_send)
##### [WSMAN_PLUGIN_SHELL](/windows/desktop/api/Wsman/nc-wsman-wsman_plugin_shell)
##### [WSMAN_PLUGIN_SHUTDOWN](/windows/desktop/api/Wsman/nc-wsman-wsman_plugin_shutdown)
##### [WSMAN_PLUGIN_SIGNAL](/windows/desktop/api/Wsman/nc-wsman-wsman_plugin_signal)
##### [WSMAN_PLUGIN_STARTUP](/windows/desktop/api/Wsman/nc-wsman-wsman_plugin_startup)
#### [Operations Plug-in Methods](operations-plug-in-methods.md)
##### [WSManPluginFreeRequestDetails](/windows/desktop/api/Wsman/nf-wsman-wsmanpluginfreerequestdetails)
##### [WSManPluginGetOperationParameters](/windows/desktop/api/Wsman/nf-wsman-wsmanplugingetoperationparameters)
##### [WSManPluginOperationComplete](/windows/desktop/api/Wsman/nf-wsman-wsmanpluginoperationcomplete)
##### [WSManPluginReceiveResult](/windows/desktop/api/Wsman/nf-wsman-wsmanpluginreceiveresult)
##### [WSManPluginReportContext](/windows/desktop/api/Wsman/nf-wsman-wsmanpluginreportcontext)
#### [WinRM Plug-in API Structures](winrm-plug-in-api-structures.md)
##### [WSMAN_AUTHZ_QUOTA](/windows/desktop/api/Wsman/ns-wsman-_wsman_authz_quota)
##### [WSMAN_CERTIFICATE_DETAILS](/windows/desktop/api/Wsman/ns-wsman-_wsman_certificate_details)
##### [WSMAN_COMMAND_ARG_SET](/windows/desktop/api/Wsman/ns-wsman-_wsman_command_arg_set)
##### [WSMAN_FILTER](/windows/desktop/api/Wsman/ns-wsman-_wsman_filter)
##### [WSMAN_FRAGMENT](/windows/desktop/api/Wsman/ns-wsman-_wsman_fragment)
##### [WSMAN_OPERATION_INFO](/windows/desktop/api/Wsman/ns-wsman-_wsman_operation_info)
##### [WSMAN_PLUGIN_REQUEST](/windows/desktop/api/Wsman/ns-wsman-_wsman_plugin_request)
##### [WSMAN_SENDER_DETAILS](/windows/desktop/api/Wsman/ns-wsman-_wsman_sender_details)
### [WinRM Scripting API](winrm-scripting-api.md)
#### [ConnectionOptions](connectionoptions.md)
##### [ConnectionOptions Properties](connectionoptions-properties.md)
###### [Password Property](connectionoptions-password.md)
###### [UserName Property](connectionoptions-username.md)
#### [Enumerator](enumerator.md)
##### [Enumerator Methods](enumerator-methods.md)
###### [ReadItem Method](enumerator-readitem.md)
##### [Enumerator Properties](enumerator-properties.md)
###### [AtEndOfStream Property](enumerator-atendofstream.md)
###### [Error Property](enumerator-error.md)
#### [ResourceLocator](resourcelocator.md)
##### [ResourceLocator Methods](resourcelocator-methods.md)
###### [AddOption Method](resourcelocator-addoption.md)
###### [AddSelector Method](resourcelocator-addselector.md)
###### [ClearOptions Method](resourcelocator-clearoptions.md)
###### [ClearSelectors Method](resourcelocator-clearselectors.md)
##### [ResourceLocator Properties](resourcelocator-properties.md)
###### [Error Property](resourcelocator-error.md)
###### [FragmentDialect Property](resourcelocator-fragmentdialect.md)
###### [FragmentPath Property](resourcelocator-fragmentpath.md)
###### [MustUnderstandOptions Property](resourcelocator-mustunderstandoptions.md)
###### [ResourceURI Property](resourcelocator-resourceuri.md)
#### [Session](session.md)
##### [Session Methods](session-methods.md)
###### [Create Method](session-create.md)
###### [Delete Method](session-delete.md)
###### [Enumerate Method](session-enumerate.md)
###### [Get Method](session-get.md)
###### [Identify Method](session-identify.md)
###### [Invoke Method](session-invoke.md)
###### [Put Method](session-put.md)
##### [Session Properties](session-properties.md)
###### [BatchItems Property](session-batchitems.md)
###### [Error Property](session-error.md)
###### [Timeout Property](session-timeout.md)
#### [WSMan](wsman.md)
##### [WSMan Methods](wsman-methods.md)
###### [CreateConnectionOptions Method](wsman-createconnectionoptions.md)
###### [CreateResourceLocator Method](wsman-createresourcelocator.md)
###### [CreateSession Method](wsman-createsession.md)
###### [EnumerationFlagHierarchyDeep Method](wsman-enumerationflaghierarchydeep.md)
###### [EnumerationFlagHierarchyDeepBasePropsOnly Method](wsman-enumerationflaghierarchydeepbasepropsonly.md)
###### [EnumerationFlagHierarchyShallow Method](wsman-enumerationflaghierarchyshallow.md)
###### [EnumerationFlagNonXmlText Method](wsman-enumerationflagnonxmltext.md)
###### [EnumerationFlagReturnEPR Method](wsman-enumerationflagreturnepr.md)
###### [EnumerationFlagReturnObject Method](wsman-enumerationflagreturnobject.md)
###### [EnumerationFlagReturnObjectAndEPR Method](wsman-enumerationflagreturnobjectandepr.md)
###### [GetErrorMessage Method](wsman-geterrormessage.md)
###### [SessionFlagCredUsernamePassword Method](wsman-sessionflagcredusernamepassword.md)
###### [SessionFlagEnableSPNServerPort Method](wsman-sessionflagenablespnserverport.md)
###### [SessionFlagNoEncryption Method](wsman-sessionflagnoencryption.md)
###### [SessionFlagSkipCACheck Method](wsman-sessionflagskipcacheck.md)
###### [SessionFlagSkipCNCheck Method](wsman-sessionflagskipcncheck.md)
###### [SessionFlagUseBasic Method](wsman-sessionflagusebasic.md)
###### [SessionFlagUseClientCertificate Method](wsman-sessionflaguseclientcert.md)
###### [SessionFlagUseCredSsp Method](wsman-sessionflagusecredssp.md)
###### [SessionFlagUseDigest Method](wsman-sessionflagusedigest.md)
###### [SessionFlagUseKerberos Method](wsman-sessionflagusekerberos.md)
###### [SessionFlagUseNegotiate Method](wsman-sessionflagusenegotiate.md)
###### [SessionFlagUseNoAuthentication Method](wsman-sessionflagusenoauthentication.md)
###### [SessionFlagUTF8 Method](wsman-sessionflagutf8.md)
##### [WSMan Properties](wsman-properties.md)
###### [CommandLine Property](wsman-commandline.md)
###### [Error Property](wsman-error.md)
### [WinRM C++ API](winrm-c---api.md)
#### [IWSMan](/windows/desktop/api/WSManDisp/nn-wsmandisp-iwsman)
##### [IWSMan Methods](iwsman-methods.md)
###### [CreateConnectionOptions Method](/windows/desktop/api/WSManDisp/nf-wsmandisp-iwsman-createconnectionoptions)
###### [CreateSession Method](/windows/desktop/api/WSManDisp/nf-wsmandisp-iwsman-createsession)
##### [IWSMan Properties](iwsman-properties.md)
###### [CommandLine Property](/windows/desktop/api/WSManDisp/nf-wsmandisp-iwsman-get_commandline)
###### [Error Property](/windows/desktop/api/WSManDisp/nf-wsmandisp-iwsman-get_error)
#### [IWSManConnectionOptions](/windows/desktop/api/WSManDisp/nn-wsmandisp-iwsmanconnectionoptions)
##### [IWSManConnectionOptions Properties](iwsmanconnectionoptions-properties.md)
###### [Password Property](/windows/desktop/api/WSManDisp/nf-wsmandisp-iwsmanconnectionoptions-put_password)
###### [UserName Property](/windows/desktop/api/WSManDisp/nf-wsmandisp-iwsmanconnectionoptions-get_username)
#### [IWSManConnectionOptionsEx](/windows/desktop/api/WSManDisp/nn-wsmandisp-iwsmanconnectionoptionsex)
##### [IWSManConnectionOptionsEx Properties](iwsmanconnectionoptionsex-properties.md)
###### [CertificateThumbprint Property](/windows/desktop/api/WSManDisp/nf-wsmandisp-iwsmanconnectionoptionsex-get_certificatethumbprint)
#### [IWSManConnectionOptionsEx2](/windows/desktop/api/WSManDisp/nn-wsmandisp-iwsmanconnectionoptionsex2)
##### [IWSManConnectionOptionsEx2 Methods](iwsmanconnectionoptionsex2-methods.md)
###### [ProxyAuthenticationUseBasic Method](/windows/desktop/api/WSManDisp/nf-wsmandisp-iwsmanconnectionoptionsex2-proxyauthenticationusebasic)
###### [ProxyAuthenticationUseDigest Method](/windows/desktop/api/WSManDisp/nf-wsmandisp-iwsmanconnectionoptionsex2-proxyauthenticationusedigest)
###### [ProxyAuthenticationUseNegotiate Method](/windows/desktop/api/WSManDisp/nf-wsmandisp-iwsmanconnectionoptionsex2-proxyauthenticationusenegotiate)
###### [ProxyAutoDetect Method](/windows/desktop/api/WSManDisp/nf-wsmandisp-iwsmanconnectionoptionsex2-proxyautodetect)
###### [ProxyIEConfig Method](/windows/desktop/api/WSManDisp/nf-wsmandisp-iwsmanconnectionoptionsex2-proxyieconfig)
###### [ProxyNoProxyServer Method](/windows/desktop/api/WSManDisp/nf-wsmandisp-iwsmanconnectionoptionsex2-proxynoproxyserver)
###### [ProxyWinHttpConfig Method](/windows/desktop/api/WSManDisp/nf-wsmandisp-iwsmanconnectionoptionsex2-proxywinhttpconfig)
###### [SetProxy Method](/windows/desktop/api/WSManDisp/nf-wsmandisp-iwsmanconnectionoptionsex2-setproxy)
#### [IWSManEnumerator](/windows/desktop/api/WSManDisp/nn-wsmandisp-iwsmanenumerator)
##### [IWSManEnumerator Methods](iwsmanenumerator-methods.md)
###### [ReadItem Method](/windows/desktop/api/WSManDisp/nf-wsmandisp-iwsmanenumerator-readitem)
##### [IWSManEnumerator Properties](iwsmanenumerator-properties.md)
###### [AtEndOfStream Property](/windows/desktop/api/WSManDisp/nf-wsmandisp-iwsmanenumerator-get_atendofstream)
###### [Error Property](/windows/desktop/api/WSManDisp/nf-wsmandisp-iwsmanenumerator-get_error)
#### [IWSManEx](/windows/desktop/api/WSManDisp/nn-wsmandisp-iwsmanex)
##### [IWSManEx Methods](iwsmanex-methods.md)
###### [CreateResourceLocator Method](/windows/desktop/api/WSManDisp/nf-wsmandisp-iwsmanex-createresourcelocator)
###### [EnumerationFlagHierarchyDeep Method](/windows/desktop/api/WSManDisp/nf-wsmandisp-iwsmanex-enumerationflaghierarchydeep)
###### [EnumerationFlagHierarchyDeepBasePropsOnly Method](/windows/desktop/api/WSManDisp/nf-wsmandisp-iwsmanex-enumerationflaghierarchydeepbasepropsonly)
###### [EnumerationFlagHierarchyShallow Method](/windows/desktop/api/WSManDisp/nf-wsmandisp-iwsmanex-enumerationflaghierarchyshallow)
###### [EnumerationFlagNonXmlText Method](/windows/desktop/api/WSManDisp/nf-wsmandisp-iwsmanex-enumerationflagnonxmltext)
###### [EnumerationFlagReturnEPR Method](/windows/desktop/api/WSManDisp/nf-wsmandisp-iwsmanex-enumerationflagreturnepr)
###### [EnumerationFlagReturnObject Method](/windows/desktop/api/WSManDisp/nf-wsmandisp-iwsmanex-enumerationflagreturnobject)
###### [EnumerationFlagReturnObjectAndEPR Method](/windows/desktop/api/WSManDisp/nf-wsmandisp-iwsmanex-enumerationflagreturnobjectandepr)
###### [GetErrorMessage Method](/windows/desktop/api/WSManDisp/nf-wsmandisp-iwsmanex-geterrormessage)
###### [SessionFlagCredUsernamePassword Method](/windows/desktop/api/WSManDisp/nf-wsmandisp-iwsmanex-sessionflagcredusernamepassword)
###### [SessionFlagEnableSPNServerPort Method](/windows/desktop/api/WSManDisp/nf-wsmandisp-iwsmanex-sessionflagenablespnserverport)
###### [SessionFlagNoEncryption Method](/windows/desktop/api/WSManDisp/nf-wsmandisp-iwsmanex-sessionflagnoencryption)
###### [SessionFlagSkipCACheck Method](/windows/desktop/api/WSManDisp/nf-wsmandisp-iwsmanex-sessionflagskipcacheck)
###### [SessionFlagSkipCNCheck Method](/windows/desktop/api/WSManDisp/nf-wsmandisp-iwsmanex-sessionflagskipcncheck)
###### [SessionFlagUseBasic Method](/windows/desktop/api/WSManDisp/nf-wsmandisp-iwsmanex-sessionflagusebasic)
###### [SessionFlagUseDigest Method](/windows/desktop/api/WSManDisp/nf-wsmandisp-iwsmanex-sessionflagusedigest)
###### [SessionFlagUseKerberos Method](/windows/desktop/api/WSManDisp/nf-wsmandisp-iwsmanex-sessionflagusekerberos)
###### [SessionFlagUseNegotiate Method](/windows/desktop/api/WSManDisp/nf-wsmandisp-iwsmanex-sessionflagusenegotiate)
###### [SessionFlagUseNoAuthentication Method](/windows/desktop/api/WSManDisp/nf-wsmandisp-iwsmanex-sessionflagusenoauthentication)
###### [SessionFlagUTF8 Method](/windows/desktop/api/WSManDisp/nf-wsmandisp-iwsmanex-sessionflagutf8)
#### [IWSManEx2](/windows/desktop/api/WSManDisp/nn-wsmandisp-iwsmanex2)
##### [IWSManEx2 Methods](iwsmanex2-methods.md)
###### [SessionFlagUseClientCertificate Method](/windows/desktop/api/WSManDisp/nf-wsmandisp-iwsmanex2-sessionflaguseclientcertificate)
#### [IWSManEx3](/windows/desktop/api/WSManDisp/nn-wsmandisp-iwsmanex3)
##### [IWSManEx3 Methods](iwsmanex3-methods.md)
###### [SessionFlagUseCredSsp Method](/windows/desktop/api/WSManDisp/nf-wsmandisp-iwsmanex3-sessionflagusecredssp)
#### [IWSManResourceLocator](/windows/desktop/api/WSManDisp/nn-wsmandisp-iwsmanresourcelocator)
##### [IWSManResourceLocator Methods](iwsmanresourcelocator-methods.md)
###### [AddOption Method](/windows/desktop/api/WSManDisp/nf-wsmandisp-iwsmanresourcelocator-addoption)
###### [AddSelector Method](/windows/desktop/api/WSManDisp/nf-wsmandisp-iwsmanresourcelocator-addselector)
###### [ClearOptions Method](/windows/desktop/api/WSManDisp/nf-wsmandisp-iwsmanresourcelocator-clearoptions)
###### [ClearSelectors Method](/windows/desktop/api/WSManDisp/nf-wsmandisp-iwsmanresourcelocator-clearselectors)
##### [IWSManResourceLocator Properties](iwsmanresourcelocator-properties.md)
###### [Error Property](/windows/desktop/api/WSManDisp/nf-wsmandisp-iwsmanresourcelocator-get_error)
###### [FragmentDialect Property](/windows/desktop/api/WSManDisp/nf-wsmandisp-iwsmanresourcelocator-get_fragmentdialect)
###### [FragmentPath Property](/windows/desktop/api/WSManDisp/nf-wsmandisp-iwsmanresourcelocator-get_fragmentpath)
###### [MustUnderstandOptions Property](/windows/desktop/api/WSManDisp/nf-wsmandisp-iwsmanresourcelocator-get_mustunderstandoptions)
###### [ResourceURI Property](/windows/desktop/api/WSManDisp/nf-wsmandisp-iwsmanresourcelocator-get_resourceuri)
#### [IWSManSession](/windows/desktop/api/WSManDisp/nn-wsmandisp-iwsmansession)
##### [IWSManSession Methods](iwsmansession-methods.md)
###### [Create Method](/windows/desktop/api/WSManDisp/nf-wsmandisp-iwsmansession-create)
###### [Delete Method](/windows/desktop/api/WSManDisp/nf-wsmandisp-iwsmansession-delete)
###### [Enumerate Method](/windows/desktop/api/WSManDisp/nf-wsmandisp-iwsmansession-enumerate)
###### [Get Method](/windows/desktop/api/WSManDisp/nf-wsmandisp-iwsmansession-get)
###### [Identify Method](/windows/desktop/api/WSManDisp/nf-wsmandisp-iwsmansession-identify)
###### [Invoke Method](/windows/desktop/api/WSManDisp/nf-wsmandisp-iwsmansession-invoke)
###### [Put Method](/windows/desktop/api/WSManDisp/nf-wsmandisp-iwsmansession-put)
##### [IWSManSession Properties](iwsmansession-properties.md)
###### [BatchItems Property](/windows/desktop/api/WSManDisp/nf-wsmandisp-iwsmansession-get_batchitems)
###### [Error Property](/windows/desktop/api/WSManDisp/nf-wsmandisp-iwsmansession-get_error)
###### [Timeout Property](/windows/desktop/api/WSManDisp/nf-wsmandisp-iwsmansession-get_timeout)
#### [WinRM Constants and Enumerations](winrm-constants-and-enumerations.md)
##### [Session Constants](session-constants.md)
###### [Authentication Constants](authentication-constants.md)
###### [Other Session Constants](other-session-constants.md)
##### [Enumeration Constants](enumeration-constants.md)
##### [WSManProxyAccessTypeFlags](/windows/desktop/api/WSManDisp/ne-wsmandisp-_wsmanproxyaccesstypeflags)
##### [WSManProxyAuthenticationFlags](/windows/desktop/api/WSManDisp/ne-wsmandisp-_wsmanproxyauthenticationflags)
### [Managed Reference for WinRM Windows PowerShell Command Classes](winrm-powershell-commandlets.md)
## [Windows Remote Management Glossary](windows-remote-management-glossary.md)
