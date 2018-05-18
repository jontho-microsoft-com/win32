---
Description: A B C D E F G H I J K L M N O P Q R S T U V W X Y Z
Robots: 'noindex, nofollow'
ms.assetid: '26e7eaae-f540-47d1-99ec-6af0fd223039'
title: D
---

# D

[A](vssgloss-a.md) [B](vssgloss-b.md) [C](vssgloss-c.md) D [E](vssgloss-e.md) [F](vssgloss-f.md) [G](vssgloss-g.md) [H](vssgloss-h.md) [I](vssgloss-i.md) J K [L](vssgloss-l.md) M [N](vssgloss-n.md) [O](vssgloss-o.md) [P](vssgloss-p.md) Q [R](vssgloss-r.md) [S](vssgloss-s.md) [T](vssgloss-t.md) U [V](vssgloss-v.md) [W](vssgloss-w.md) X Y Z

<dl> <dt>

<span id="base.vssgloss_database_component"></span><span id="BASE.VSSGLOSS_DATABASE_COMPONENT"></span>**database component**
</dt> <dd>

A group of files used by a database and defined by a writer as needing to be handled as a unit during backup and restore operations. See also [*component*](vssgloss-c.md#base-vssgloss-component), [*file group component*](vssgloss-f.md#base-vssgloss-file-group-component).

</dd> <dt>

<span id="base.vssgloss_default_provider"></span><span id="BASE.VSSGLOSS_DEFAULT_PROVIDER"></span>**default provider**
</dt> <dd>

See [*system provider*](vssgloss-s.md#base-vssgloss-system-provider).

</dd> <dt>

<span id="base.vssgloss_deleted_shadow_copy"></span><span id="BASE.VSSGLOSS_DELETED_SHADOW_COPY"></span>**deleted shadow copy**
</dt> <dd>

Deleted shadow copies are not accessible at all and must not be made accessible at any time in the future.

</dd> <dt>

<span id="base.vssgloss_dependency"></span><span id="BASE.VSSGLOSS_DEPENDENCY"></span>**dependency**
</dt> <dd>

See [*component dependency*](vssgloss-c.md#base-vssgloss-component-dependency).

</dd> <dt>

<span id="base.vssgloss_device_object"></span><span id="BASE.VSSGLOSS_DEVICE_OBJECT"></span>**device object**
</dt> <dd>

A string indicating the "root" of a shadow copied volume. Files and directories on a shadow copied volume can be referenced by prepending the device object string to a corresponding path on the original volume. As obtained as the **m\_pwszSnapshotDeviceObject** member of the [**VSS\_SNAPSHOT\_PROP**](vss-snapshot-prop.md) structure, the device object has no backslash ("\\").

</dd> <dt>

<span id="base.vssgloss_diff_area"></span><span id="BASE.VSSGLOSS_DIFF_AREA"></span>**diff area**
</dt> <dd>

The location on the volume where the *differential data* is stored. This is also known as shadow copy storage space.

</dd> <dt>

<span id="base.vssgloss_differenced_files"></span><span id="BASE.VSSGLOSS_DIFFERENCED_FILES"></span>**differenced files**
</dt> <dd>

Files involved in an incremental or differential backup operation implemented by updating entire files (as opposed to modifying sections of those files using partial file support). For instance, if to implement a differential backup an entire file (instead of just the modified section) is copied to a backup media, that file is a differenced file. See also [*incremental backup operations*](vssgloss-i.md#base-vssgloss-incremental-backup-operations), *differential backup operations*, [*partial file support*](vssgloss-p.md#base-vssgloss-partial-file-support).

</dd> <dt>

<span id="base.vssgloss_differential_backup_operations"></span><span id="BASE.VSSGLOSS_DIFFERENTIAL_BACKUP_OPERATIONS"></span>**differential backup operations**
</dt> <dd>

A backup or restore operation performed only on files created or changed since the last full backup was saved. See also [*incremental backup operations*](vssgloss-i.md#base-vssgloss-incremental-backup-operations), [*partial file support*](vssgloss-p.md#base-vssgloss-partial-file-support), *differenced files*.

</dd> <dt>

<span id="base.vssgloss_differential_data"></span><span id="BASE.VSSGLOSS_DIFFERENTIAL_DATA"></span>**differential data**
</dt> <dd>

Data that can be applied to an original volume to generate a shadow copy volume. This is also commonly known as copy-on-write data, but this documentation uses the term differential data.

</dd> <dt>

<span id="base.vssgloss_directed_targeting"></span><span id="BASE.VSSGLOSS_DIRECTED_TARGETING"></span>**directed targeting**
</dt> <dd>

A restoration mode by which a writer indicates that when a file is to be restored, it (the source file) should be remapped. The file may be restored to a new restore location and/or ranges of its data restored to different offset with the restore location.

</dd> </dl>

 

 


