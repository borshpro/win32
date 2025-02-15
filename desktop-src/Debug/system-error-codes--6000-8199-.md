---
description: Describes error codes 6000-8199 defined in the WinError.h header file and is intended for developers.
ms.assetid: eaaf9f65-e8ff-4e54-90a9-04252cdd773a
title: System Error Codes (6000-8199) (WinError.h)
ms.topic: reference
ms.date: 07/15/2024
---

# System Error Codes (6000-8199)

The following list describes [system error codes](system-error-codes.md) (errors 6000 to 8199). They are returned by the [**GetLastError**](/windows/win32/api/errhandlingapi/nf-errhandlingapi-getlasterror) function when many functions fail. To retrieve the description text for the error in your application, use the [**FormatMessage**](/windows/desktop/api/WinBase/nf-winbase-formatmessage) function with the **FORMAT\_MESSAGE\_FROM\_SYSTEM** flag.

> [!NOTE]
> This information is intended for developers debugging system errors. For other errors, such as issues with Windows Update, see the list of resources on the [Error codes](system-error-codes.md) page.

 

<span id="ERROR_ENCRYPTION_FAILED"></span><span id="error_encryption_failed"></span>**ERROR\_ENCRYPTION\_FAILED**
   

6000 (0x1770)
 



The specified file could not be encrypted.


   

<span id="ERROR_DECRYPTION_FAILED"></span><span id="error_decryption_failed"></span>**ERROR\_DECRYPTION\_FAILED**
   

6001 (0x1771)
 



The specified file could not be decrypted.


   

<span id="ERROR_FILE_ENCRYPTED"></span><span id="error_file_encrypted"></span>**ERROR\_FILE\_ENCRYPTED**
   

6002 (0x1772)
 



The specified file is encrypted and the user does not have the ability to decrypt it.


   

<span id="ERROR_NO_RECOVERY_POLICY"></span><span id="error_no_recovery_policy"></span>**ERROR\_NO\_RECOVERY\_POLICY**
   

6003 (0x1773)
 



There is no valid encryption recovery policy configured for this system.


   

<span id="ERROR_NO_EFS"></span><span id="error_no_efs"></span>**ERROR\_NO\_EFS**
   

6004 (0x1774)
 



The required encryption driver is not loaded for this system.


   

<span id="ERROR_WRONG_EFS"></span><span id="error_wrong_efs"></span>**ERROR\_WRONG\_EFS**
   

6005 (0x1775)
 



The file was encrypted with a different encryption driver than is currently loaded.


   

<span id="ERROR_NO_USER_KEYS"></span><span id="error_no_user_keys"></span>**ERROR\_NO\_USER\_KEYS**
   

6006 (0x1776)
 



There are no EFS keys defined for the user.


   

<span id="ERROR_FILE_NOT_ENCRYPTED"></span><span id="error_file_not_encrypted"></span>**ERROR\_FILE\_NOT\_ENCRYPTED**
   

6007 (0x1777)
 



The specified file is not encrypted.


   

<span id="ERROR_NOT_EXPORT_FORMAT"></span><span id="error_not_export_format"></span>**ERROR\_NOT\_EXPORT\_FORMAT**
   

6008 (0x1778)
 



The specified file is not in the defined EFS export format.


   

<span id="ERROR_FILE_READ_ONLY"></span><span id="error_file_read_only"></span>**ERROR\_FILE\_READ\_ONLY**
   

6009 (0x1779)
 



The specified file is read only.


   

<span id="ERROR_DIR_EFS_DISALLOWED"></span><span id="error_dir_efs_disallowed"></span>**ERROR\_DIR\_EFS\_DISALLOWED**
   

6010 (0x177A)
 



The directory has been disabled for encryption.


   

<span id="ERROR_EFS_SERVER_NOT_TRUSTED"></span><span id="error_efs_server_not_trusted"></span>**ERROR\_EFS\_SERVER\_NOT\_TRUSTED**
   

6011 (0x177B)
 



The server is not trusted for remote encryption operation.


   

<span id="ERROR_BAD_RECOVERY_POLICY"></span><span id="error_bad_recovery_policy"></span>**ERROR\_BAD\_RECOVERY\_POLICY**
   

6012 (0x177C)
 



Recovery policy configured for this system contains invalid recovery certificate.


   

<span id="ERROR_EFS_ALG_BLOB_TOO_BIG"></span><span id="error_efs_alg_blob_too_big"></span>**ERROR\_EFS\_ALG\_BLOB\_TOO\_BIG**
   

6013 (0x177D)
 



The encryption algorithm used on the source file needs a bigger key buffer than the one on the destination file.


   

<span id="ERROR_VOLUME_NOT_SUPPORT_EFS"></span><span id="error_volume_not_support_efs"></span>**ERROR\_VOLUME\_NOT\_SUPPORT\_EFS**
   

6014 (0x177E)
 



The disk partition does not support file encryption.


   

<span id="ERROR_EFS_DISABLED"></span><span id="error_efs_disabled"></span>**ERROR\_EFS\_DISABLED**
   

6015 (0x177F)
 



This machine is disabled for file encryption.


   

<span id="ERROR_EFS_VERSION_NOT_SUPPORT"></span><span id="error_efs_version_not_support"></span>**ERROR\_EFS\_VERSION\_NOT\_SUPPORT**
   

6016 (0x1780)
 



A newer system is required to decrypt this encrypted file.


   

<span id="ERROR_CS_ENCRYPTION_INVALID_SERVER_RESPONSE"></span><span id="error_cs_encryption_invalid_server_response"></span>**ERROR\_CS\_ENCRYPTION\_INVALID\_SERVER\_RESPONSE**
   

6017 (0x1781)
 



The remote server sent an invalid response for a file being opened with Client Side Encryption.


   

<span id="ERROR_CS_ENCRYPTION_UNSUPPORTED_SERVER"></span><span id="error_cs_encryption_unsupported_server"></span>**ERROR\_CS\_ENCRYPTION\_UNSUPPORTED\_SERVER**
   

6018 (0x1782)
 



Client Side Encryption is not supported by the remote server even though it claims to support it.


   

<span id="ERROR_CS_ENCRYPTION_EXISTING_ENCRYPTED_FILE"></span><span id="error_cs_encryption_existing_encrypted_file"></span>**ERROR\_CS\_ENCRYPTION\_EXISTING\_ENCRYPTED\_FILE**
   

6019 (0x1783)
 



File is encrypted and should be opened in Client Side Encryption mode.


   

<span id="ERROR_CS_ENCRYPTION_NEW_ENCRYPTED_FILE"></span><span id="error_cs_encryption_new_encrypted_file"></span>**ERROR\_CS\_ENCRYPTION\_NEW\_ENCRYPTED\_FILE**
   

6020 (0x1784)
 



A new encrypted file is being created and a $EFS needs to be provided.


   

<span id="ERROR_CS_ENCRYPTION_FILE_NOT_CSE"></span><span id="error_cs_encryption_file_not_cse"></span>**ERROR\_CS\_ENCRYPTION\_FILE\_NOT\_CSE**
   

6021 (0x1785)
 



The SMB client requested a CSE FSCTL on a non-CSE file.


   

<span id="ERROR_ENCRYPTION_POLICY_DENIES_OPERATION"></span><span id="error_encryption_policy_denies_operation"></span>**ERROR\_ENCRYPTION\_POLICY\_DENIES\_OPERATION**
   

6022 (0x1786)
 



The requested operation was blocked by policy. For more information, contact your system administrator.


   

<span id="ERROR_NO_BROWSER_SERVERS_FOUND"></span><span id="error_no_browser_servers_found"></span>**ERROR\_NO\_BROWSER\_SERVERS\_FOUND**
   

6118 (0x17E6)
 



The list of servers for this workgroup is not currently available.


   

<span id="SCHED_E_SERVICE_NOT_LOCALSYSTEM"></span><span id="sched_e_service_not_localsystem"></span>**SCHED\_E\_SERVICE\_NOT\_LOCALSYSTEM**
   

6200 (0x1838)
 



The Task Scheduler service must be configured to run in the System account to function properly. Individual tasks may be configured to run in other accounts.


   

<span id="ERROR_LOG_SECTOR_INVALID"></span><span id="error_log_sector_invalid"></span>**ERROR\_LOG\_SECTOR\_INVALID**
   

6600 (0x19C8)
 



Log service encountered an invalid log sector.


   

<span id="ERROR_LOG_SECTOR_PARITY_INVALID"></span><span id="error_log_sector_parity_invalid"></span>**ERROR\_LOG\_SECTOR\_PARITY\_INVALID**
   

6601 (0x19C9)
 



Log service encountered a log sector with invalid block parity.


   

<span id="ERROR_LOG_SECTOR_REMAPPED"></span><span id="error_log_sector_remapped"></span>**ERROR\_LOG\_SECTOR\_REMAPPED**
   

6602 (0x19CA)
 



Log service encountered a remapped log sector.


   

<span id="ERROR_LOG_BLOCK_INCOMPLETE"></span><span id="error_log_block_incomplete"></span>**ERROR\_LOG\_BLOCK\_INCOMPLETE**
   

6603 (0x19CB)
 



Log service encountered a partial or incomplete log block.


   

<span id="ERROR_LOG_INVALID_RANGE"></span><span id="error_log_invalid_range"></span>**ERROR\_LOG\_INVALID\_RANGE**
   

6604 (0x19CC)
 



Log service encountered an attempt access data outside the active log range.


   

<span id="ERROR_LOG_BLOCKS_EXHAUSTED"></span><span id="error_log_blocks_exhausted"></span>**ERROR\_LOG\_BLOCKS\_EXHAUSTED**
   

6605 (0x19CD)
 



Log service user marshalling buffers are exhausted.


   

<span id="ERROR_LOG_READ_CONTEXT_INVALID"></span><span id="error_log_read_context_invalid"></span>**ERROR\_LOG\_READ\_CONTEXT\_INVALID**
   

6606 (0x19CE)
 



Log service encountered an attempt read from a marshalling area with an invalid read context.


   

<span id="ERROR_LOG_RESTART_INVALID"></span><span id="error_log_restart_invalid"></span>**ERROR\_LOG\_RESTART\_INVALID**
   

6607 (0x19CF)
 



Log service encountered an invalid log restart area.


   

<span id="ERROR_LOG_BLOCK_VERSION"></span><span id="error_log_block_version"></span>**ERROR\_LOG\_BLOCK\_VERSION**
   

6608 (0x19D0)
 



Log service encountered an invalid log block version.


   

<span id="ERROR_LOG_BLOCK_INVALID"></span><span id="error_log_block_invalid"></span>**ERROR\_LOG\_BLOCK\_INVALID**
   

6609 (0x19D1)
 



Log service encountered an invalid log block.


   

<span id="ERROR_LOG_READ_MODE_INVALID"></span><span id="error_log_read_mode_invalid"></span>**ERROR\_LOG\_READ\_MODE\_INVALID**
   

6610 (0x19D2)
 



Log service encountered an attempt to read the log with an invalid read mode.


   

<span id="ERROR_LOG_NO_RESTART"></span><span id="error_log_no_restart"></span>**ERROR\_LOG\_NO\_RESTART**
   

6611 (0x19D3)
 



Log service encountered a log stream with no restart area.


   

<span id="ERROR_LOG_METADATA_CORRUPT"></span><span id="error_log_metadata_corrupt"></span>**ERROR\_LOG\_METADATA\_CORRUPT**
   

6612 (0x19D4)
 



Log service encountered a corrupted metadata file.


   

<span id="ERROR_LOG_METADATA_INVALID"></span><span id="error_log_metadata_invalid"></span>**ERROR\_LOG\_METADATA\_INVALID**
   

6613 (0x19D5)
 



Log service encountered a metadata file that could not be created by the log file system.


   

<span id="ERROR_LOG_METADATA_INCONSISTENT"></span><span id="error_log_metadata_inconsistent"></span>**ERROR\_LOG\_METADATA\_INCONSISTENT**
   

6614 (0x19D6)
 



Log service encountered a metadata file with inconsistent data.


   

<span id="ERROR_LOG_RESERVATION_INVALID"></span><span id="error_log_reservation_invalid"></span>**ERROR\_LOG\_RESERVATION\_INVALID**
   

6615 (0x19D7)
 



Log service encountered an attempt to erroneous allocate or dispose reservation space.


   

<span id="ERROR_LOG_CANT_DELETE"></span><span id="error_log_cant_delete"></span>**ERROR\_LOG\_CANT\_DELETE**
   

6616 (0x19D8)
 



Log service cannot delete log file or file system container.


   

<span id="ERROR_LOG_CONTAINER_LIMIT_EXCEEDED"></span><span id="error_log_container_limit_exceeded"></span>**ERROR\_LOG\_CONTAINER\_LIMIT\_EXCEEDED**
   

6617 (0x19D9)
 



Log service has reached the maximum allowable containers allocated to a log file.


   

<span id="ERROR_LOG_START_OF_LOG"></span><span id="error_log_start_of_log"></span>**ERROR\_LOG\_START\_OF\_LOG**
   

6618 (0x19DA)
 



Log service has attempted to read or write backward past the start of the log.


   

<span id="ERROR_LOG_POLICY_ALREADY_INSTALLED"></span><span id="error_log_policy_already_installed"></span>**ERROR\_LOG\_POLICY\_ALREADY\_INSTALLED**
   

6619 (0x19DB)
 



Log policy could not be installed because a policy of the same type is already present.


   

<span id="ERROR_LOG_POLICY_NOT_INSTALLED"></span><span id="error_log_policy_not_installed"></span>**ERROR\_LOG\_POLICY\_NOT\_INSTALLED**
   

6620 (0x19DC)
 



Log policy in question was not installed at the time of the request.


   

<span id="ERROR_LOG_POLICY_INVALID"></span><span id="error_log_policy_invalid"></span>**ERROR\_LOG\_POLICY\_INVALID**
   

6621 (0x19DD)
 



The installed set of policies on the log is invalid.


   

<span id="ERROR_LOG_POLICY_CONFLICT"></span><span id="error_log_policy_conflict"></span>**ERROR\_LOG\_POLICY\_CONFLICT**
   

6622 (0x19DE)
 



A policy on the log in question prevented the operation from completing.


   

<span id="ERROR_LOG_PINNED_ARCHIVE_TAIL"></span><span id="error_log_pinned_archive_tail"></span>**ERROR\_LOG\_PINNED\_ARCHIVE\_TAIL**
   

6623 (0x19DF)
 



Log space cannot be reclaimed because the log is pinned by the archive tail.


   

<span id="ERROR_LOG_RECORD_NONEXISTENT"></span><span id="error_log_record_nonexistent"></span>**ERROR\_LOG\_RECORD\_NONEXISTENT**
   

6624 (0x19E0)
 



Log record is not a record in the log file.


   

<span id="ERROR_LOG_RECORDS_RESERVED_INVALID"></span><span id="error_log_records_reserved_invalid"></span>**ERROR\_LOG\_RECORDS\_RESERVED\_INVALID**
   

6625 (0x19E1)
 



Number of reserved log records or the adjustment of the number of reserved log records is invalid.


   

<span id="ERROR_LOG_SPACE_RESERVED_INVALID"></span><span id="error_log_space_reserved_invalid"></span>**ERROR\_LOG\_SPACE\_RESERVED\_INVALID**
   

6626 (0x19E2)
 



Reserved log space or the adjustment of the log space is invalid.


   

<span id="ERROR_LOG_TAIL_INVALID"></span><span id="error_log_tail_invalid"></span>**ERROR\_LOG\_TAIL\_INVALID**
   

6627 (0x19E3)
 



An new or existing archive tail or base of the active log is invalid.


   

<span id="ERROR_LOG_FULL"></span><span id="error_log_full"></span>**ERROR\_LOG\_FULL**
   

6628 (0x19E4)
 



Log space is exhausted.


   

<span id="ERROR_COULD_NOT_RESIZE_LOG"></span><span id="error_could_not_resize_log"></span>**ERROR\_COULD\_NOT\_RESIZE\_LOG**
   

6629 (0x19E5)
 



The log could not be set to the requested size.


   

<span id="ERROR_LOG_MULTIPLEXED"></span><span id="error_log_multiplexed"></span>**ERROR\_LOG\_MULTIPLEXED**
   

6630 (0x19E6)
 



Log is multiplexed, no direct writes to the physical log is allowed.


   

<span id="ERROR_LOG_DEDICATED"></span><span id="error_log_dedicated"></span>**ERROR\_LOG\_DEDICATED**
   

6631 (0x19E7)
 



The operation failed because the log is a dedicated log.


   

<span id="ERROR_LOG_ARCHIVE_NOT_IN_PROGRESS"></span><span id="error_log_archive_not_in_progress"></span>**ERROR\_LOG\_ARCHIVE\_NOT\_IN\_PROGRESS**
   

6632 (0x19E8)
 



The operation requires an archive context.


   

<span id="ERROR_LOG_ARCHIVE_IN_PROGRESS"></span><span id="error_log_archive_in_progress"></span>**ERROR\_LOG\_ARCHIVE\_IN\_PROGRESS**
   

6633 (0x19E9)
 



Log archival is in progress.


   

<span id="ERROR_LOG_EPHEMERAL"></span><span id="error_log_ephemeral"></span>**ERROR\_LOG\_EPHEMERAL**
   

6634 (0x19EA)
 



The operation requires a non-ephemeral log, but the log is ephemeral.


   

<span id="ERROR_LOG_NOT_ENOUGH_CONTAINERS"></span><span id="error_log_not_enough_containers"></span>**ERROR\_LOG\_NOT\_ENOUGH\_CONTAINERS**
   

6635 (0x19EB)
 



The log must have at least two containers before it can be read from or written to.


   

<span id="ERROR_LOG_CLIENT_ALREADY_REGISTERED"></span><span id="error_log_client_already_registered"></span>**ERROR\_LOG\_CLIENT\_ALREADY\_REGISTERED**
   

6636 (0x19EC)
 



A log client has already registered on the stream.


   

<span id="ERROR_LOG_CLIENT_NOT_REGISTERED"></span><span id="error_log_client_not_registered"></span>**ERROR\_LOG\_CLIENT\_NOT\_REGISTERED**
   

6637 (0x19ED)
 



A log client has not been registered on the stream.


   

<span id="ERROR_LOG_FULL_HANDLER_IN_PROGRESS"></span><span id="error_log_full_handler_in_progress"></span>**ERROR\_LOG\_FULL\_HANDLER\_IN\_PROGRESS**
   

6638 (0x19EE)
 



A request has already been made to handle the log full condition.


   

<span id="ERROR_LOG_CONTAINER_READ_FAILED"></span><span id="error_log_container_read_failed"></span>**ERROR\_LOG\_CONTAINER\_READ\_FAILED**
   

6639 (0x19EF)
 



Log service encountered an error when attempting to read from a log container.


   

<span id="ERROR_LOG_CONTAINER_WRITE_FAILED"></span><span id="error_log_container_write_failed"></span>**ERROR\_LOG\_CONTAINER\_WRITE\_FAILED**
   

6640 (0x19F0)
 



Log service encountered an error when attempting to write to a log container.


   

<span id="ERROR_LOG_CONTAINER_OPEN_FAILED"></span><span id="error_log_container_open_failed"></span>**ERROR\_LOG\_CONTAINER\_OPEN\_FAILED**
   

6641 (0x19F1)
 



Log service encountered an error when attempting open a log container.


   

<span id="ERROR_LOG_CONTAINER_STATE_INVALID"></span><span id="error_log_container_state_invalid"></span>**ERROR\_LOG\_CONTAINER\_STATE\_INVALID**
   

6642 (0x19F2)
 



Log service encountered an invalid container state when attempting a requested action.


   

<span id="ERROR_LOG_STATE_INVALID"></span><span id="error_log_state_invalid"></span>**ERROR\_LOG\_STATE\_INVALID**
   

6643 (0x19F3)
 



Log service is not in the correct state to perform a requested action.


   

<span id="ERROR_LOG_PINNED"></span><span id="error_log_pinned"></span>**ERROR\_LOG\_PINNED**
   

6644 (0x19F4)
 



Log space cannot be reclaimed because the log is pinned.


   

<span id="ERROR_LOG_METADATA_FLUSH_FAILED"></span><span id="error_log_metadata_flush_failed"></span>**ERROR\_LOG\_METADATA\_FLUSH\_FAILED**
   

6645 (0x19F5)
 



Log metadata flush failed.


   

<span id="ERROR_LOG_INCONSISTENT_SECURITY"></span><span id="error_log_inconsistent_security"></span>**ERROR\_LOG\_INCONSISTENT\_SECURITY**
   

6646 (0x19F6)
 



Security on the log and its containers is inconsistent.


   

<span id="ERROR_LOG_APPENDED_FLUSH_FAILED"></span><span id="error_log_appended_flush_failed"></span>**ERROR\_LOG\_APPENDED\_FLUSH\_FAILED**
   

6647 (0x19F7)
 



Records were appended to the log or reservation changes were made, but the log could not be flushed.


   

<span id="ERROR_LOG_PINNED_RESERVATION"></span><span id="error_log_pinned_reservation"></span>**ERROR\_LOG\_PINNED\_RESERVATION**
   

6648 (0x19F8)
 



The log is pinned due to reservation consuming most of the log space. Free some reserved records to make space available.


   

<span id="ERROR_INVALID_TRANSACTION"></span><span id="error_invalid_transaction"></span>**ERROR\_INVALID\_TRANSACTION**
   

6700 (0x1A2C)
 



The transaction handle associated with this operation is not valid.


   

<span id="ERROR_TRANSACTION_NOT_ACTIVE"></span><span id="error_transaction_not_active"></span>**ERROR\_TRANSACTION\_NOT\_ACTIVE**
   

6701 (0x1A2D)
 



The requested operation was made in the context of a transaction that is no longer active.


   

<span id="ERROR_TRANSACTION_REQUEST_NOT_VALID"></span><span id="error_transaction_request_not_valid"></span>**ERROR\_TRANSACTION\_REQUEST\_NOT\_VALID**
   

6702 (0x1A2E)
 



The requested operation is not valid on the Transaction object in its current state.


   

<span id="ERROR_TRANSACTION_NOT_REQUESTED"></span><span id="error_transaction_not_requested"></span>**ERROR\_TRANSACTION\_NOT\_REQUESTED**
   

6703 (0x1A2F)
 



The caller has called a response API, but the response is not expected because the TM did not issue the corresponding request to the caller.


   

<span id="ERROR_TRANSACTION_ALREADY_ABORTED"></span><span id="error_transaction_already_aborted"></span>**ERROR\_TRANSACTION\_ALREADY\_ABORTED**
   

6704 (0x1A30)
 



It is too late to perform the requested operation, since the Transaction has already been aborted.


   

<span id="ERROR_TRANSACTION_ALREADY_COMMITTED"></span><span id="error_transaction_already_committed"></span>**ERROR\_TRANSACTION\_ALREADY\_COMMITTED**
   

6705 (0x1A31)
 



It is too late to perform the requested operation, since the Transaction has already been committed.


   

<span id="ERROR_TM_INITIALIZATION_FAILED"></span><span id="error_tm_initialization_failed"></span>**ERROR\_TM\_INITIALIZATION\_FAILED**
   

6706 (0x1A32)
 



The Transaction Manager was unable to be successfully initialized. Transacted operations are not supported.


   

<span id="ERROR_RESOURCEMANAGER_READ_ONLY"></span><span id="error_resourcemanager_read_only"></span>**ERROR\_RESOURCEMANAGER\_READ\_ONLY**
   

6707 (0x1A33)
 



The specified ResourceManager made no changes or updates to the resource under this transaction.


   

<span id="ERROR_TRANSACTION_NOT_JOINED"></span><span id="error_transaction_not_joined"></span>**ERROR\_TRANSACTION\_NOT\_JOINED**
   

6708 (0x1A34)
 



The resource manager has attempted to prepare a transaction that it has not successfully joined.


   

<span id="ERROR_TRANSACTION_SUPERIOR_EXISTS"></span><span id="error_transaction_superior_exists"></span>**ERROR\_TRANSACTION\_SUPERIOR\_EXISTS**
   

6709 (0x1A35)
 



The Transaction object already has a superior enlistment, and the caller attempted an operation that would have created a new superior. Only a single superior enlistment is allow.


   

<span id="ERROR_CRM_PROTOCOL_ALREADY_EXISTS"></span><span id="error_crm_protocol_already_exists"></span>**ERROR\_CRM\_PROTOCOL\_ALREADY\_EXISTS**
   

6710 (0x1A36)
 



The RM tried to register a protocol that already exists.


   

<span id="ERROR_TRANSACTION_PROPAGATION_FAILED"></span><span id="error_transaction_propagation_failed"></span>**ERROR\_TRANSACTION\_PROPAGATION\_FAILED**
   

6711 (0x1A37)
 



The attempt to propagate the Transaction failed.


   

<span id="ERROR_CRM_PROTOCOL_NOT_FOUND"></span><span id="error_crm_protocol_not_found"></span>**ERROR\_CRM\_PROTOCOL\_NOT\_FOUND**
   

6712 (0x1A38)
 



The requested propagation protocol was not registered as a CRM.


   

<span id="ERROR_TRANSACTION_INVALID_MARSHALL_BUFFER"></span><span id="error_transaction_invalid_marshall_buffer"></span>**ERROR\_TRANSACTION\_INVALID\_MARSHALL\_BUFFER**
   

6713 (0x1A39)
 



The buffer passed in to PushTransaction or PullTransaction is not in a valid format.


   

<span id="ERROR_CURRENT_TRANSACTION_NOT_VALID"></span><span id="error_current_transaction_not_valid"></span>**ERROR\_CURRENT\_TRANSACTION\_NOT\_VALID**
   

6714 (0x1A3A)
 



The current transaction context associated with the thread is not a valid handle to a transaction object.


   

<span id="ERROR_TRANSACTION_NOT_FOUND"></span><span id="error_transaction_not_found"></span>**ERROR\_TRANSACTION\_NOT\_FOUND**
   

6715 (0x1A3B)
 



The specified Transaction object could not be opened, because it was not found.


   

<span id="ERROR_RESOURCEMANAGER_NOT_FOUND"></span><span id="error_resourcemanager_not_found"></span>**ERROR\_RESOURCEMANAGER\_NOT\_FOUND**
   

6716 (0x1A3C)
 



The specified ResourceManager object could not be opened, because it was not found.


   

<span id="ERROR_ENLISTMENT_NOT_FOUND"></span><span id="error_enlistment_not_found"></span>**ERROR\_ENLISTMENT\_NOT\_FOUND**
   

6717 (0x1A3D)
 



The specified Enlistment object could not be opened, because it was not found.


   

<span id="ERROR_TRANSACTIONMANAGER_NOT_FOUND"></span><span id="error_transactionmanager_not_found"></span>**ERROR\_TRANSACTIONMANAGER\_NOT\_FOUND**
   

6718 (0x1A3E)
 



The specified TransactionManager object could not be opened, because it was not found.


   

<span id="ERROR_TRANSACTIONMANAGER_NOT_ONLINE"></span><span id="error_transactionmanager_not_online"></span>**ERROR\_TRANSACTIONMANAGER\_NOT\_ONLINE**
   

6719 (0x1A3F)
 



The object specified could not be created or opened, because its associated TransactionManager is not online. The TransactionManager must be brought fully Online by calling RecoverTransactionManager to recover to the end of its LogFile before objects in its Transaction or ResourceManager namespaces can be opened. In addition, errors in writing records to its LogFile can cause a TransactionManager to go offline.


   

<span id="ERROR_TRANSACTIONMANAGER_RECOVERY_NAME_COLLISION"></span><span id="error_transactionmanager_recovery_name_collision"></span>**ERROR\_TRANSACTIONMANAGER\_RECOVERY\_NAME\_COLLISION**
   

6720 (0x1A40)
 



The specified TransactionManager was unable to create the objects contained in its logfile in the Ob namespace. Therefore, the TransactionManager was unable to recover.


   

<span id="ERROR_TRANSACTION_NOT_ROOT"></span><span id="error_transaction_not_root"></span>**ERROR\_TRANSACTION\_NOT\_ROOT**
   

6721 (0x1A41)
 



The call to create a superior Enlistment on this Transaction object could not be completed, because the Transaction object specified for the enlistment is a subordinate branch of the Transaction. Only the root of the Transaction can be enlisted on as a superior.


   

<span id="ERROR_TRANSACTION_OBJECT_EXPIRED"></span><span id="error_transaction_object_expired"></span>**ERROR\_TRANSACTION\_OBJECT\_EXPIRED**
   

6722 (0x1A42)
 



Because the associated transaction manager or resource manager has been closed, the handle is no longer valid.


   

<span id="ERROR_TRANSACTION_RESPONSE_NOT_ENLISTED"></span><span id="error_transaction_response_not_enlisted"></span>**ERROR\_TRANSACTION\_RESPONSE\_NOT\_ENLISTED**
   

6723 (0x1A43)
 



The specified operation could not be performed on this Superior enlistment, because the enlistment was not created with the corresponding completion response in the NotificationMask.


   

<span id="ERROR_TRANSACTION_RECORD_TOO_LONG"></span><span id="error_transaction_record_too_long"></span>**ERROR\_TRANSACTION\_RECORD\_TOO\_LONG**
   

6724 (0x1A44)
 



The specified operation could not be performed, because the record that would be logged was too long. This can occur because of two conditions: either there are too many Enlistments on this Transaction, or the combined RecoveryInformation being logged on behalf of those Enlistments is too long.


   

<span id="ERROR_IMPLICIT_TRANSACTION_NOT_SUPPORTED"></span><span id="error_implicit_transaction_not_supported"></span>**ERROR\_IMPLICIT\_TRANSACTION\_NOT\_SUPPORTED**
   

6725 (0x1A45)
 



Implicit transaction are not supported.


   

<span id="ERROR_TRANSACTION_INTEGRITY_VIOLATED"></span><span id="error_transaction_integrity_violated"></span>**ERROR\_TRANSACTION\_INTEGRITY\_VIOLATED**
   

6726 (0x1A46)
 



The kernel transaction manager had to abort or forget the transaction because it blocked forward progress.


   

<span id="ERROR_TRANSACTIONMANAGER_IDENTITY_MISMATCH"></span><span id="error_transactionmanager_identity_mismatch"></span>**ERROR\_TRANSACTIONMANAGER\_IDENTITY\_MISMATCH**
   

6727 (0x1A47)
 



The TransactionManager identity that was supplied did not match the one recorded in the TransactionManager's log file.


   

<span id="ERROR_RM_CANNOT_BE_FROZEN_FOR_SNAPSHOT"></span><span id="error_rm_cannot_be_frozen_for_snapshot"></span>**ERROR\_RM\_CANNOT\_BE\_FROZEN\_FOR\_SNAPSHOT**
   

6728 (0x1A48)
 



This snapshot operation cannot continue because a transactional resource manager cannot be frozen in its current state. Please try again.


   

<span id="ERROR_TRANSACTION_MUST_WRITETHROUGH"></span><span id="error_transaction_must_writethrough"></span>**ERROR\_TRANSACTION\_MUST\_WRITETHROUGH**
   

6729 (0x1A49)
 



The transaction cannot be enlisted on with the specified EnlistmentMask, because the transaction has already completed the PrePrepare phase. In order to ensure correctness, the ResourceManager must switch to a write- through mode and cease caching data within this transaction. Enlisting for only subsequent transaction phases may still succeed.


   

<span id="ERROR_TRANSACTION_NO_SUPERIOR"></span><span id="error_transaction_no_superior"></span>**ERROR\_TRANSACTION\_NO\_SUPERIOR**
   

6730 (0x1A4A)
 



The transaction does not have a superior enlistment.


   

<span id="ERROR_HEURISTIC_DAMAGE_POSSIBLE"></span><span id="error_heuristic_damage_possible"></span>**ERROR\_HEURISTIC\_DAMAGE\_POSSIBLE**
   

6731 (0x1A4B)
 



The attempt to commit the Transaction completed, but it is possible that some portion of the transaction tree did not commit successfully due to heuristics. Therefore it is possible that some data modified in the transaction may not have committed, resulting in transactional inconsistency. If possible, check the consistency of the associated data.


   

<span id="ERROR_TRANSACTIONAL_CONFLICT"></span><span id="error_transactional_conflict"></span>**ERROR\_TRANSACTIONAL\_CONFLICT**
   

6800 (0x1A90)
 



The function attempted to use a name that is reserved for use by another transaction.


   

<span id="ERROR_RM_NOT_ACTIVE"></span><span id="error_rm_not_active"></span>**ERROR\_RM\_NOT\_ACTIVE**
   

6801 (0x1A91)
 



Transaction support within the specified resource manager is not started or was shut down due to an error.


   

<span id="ERROR_RM_METADATA_CORRUPT"></span><span id="error_rm_metadata_corrupt"></span>**ERROR\_RM\_METADATA\_CORRUPT**
   

6802 (0x1A92)
 



The metadata of the RM has been corrupted. The RM will not function.


   

<span id="ERROR_DIRECTORY_NOT_RM"></span><span id="error_directory_not_rm"></span>**ERROR\_DIRECTORY\_NOT\_RM**
   

6803 (0x1A93)
 



The specified directory does not contain a resource manager.


   

<span id="ERROR_TRANSACTIONS_UNSUPPORTED_REMOTE"></span><span id="error_transactions_unsupported_remote"></span>**ERROR\_TRANSACTIONS\_UNSUPPORTED\_REMOTE**
   

6805 (0x1A95)
 



The remote server or share does not support transacted file operations.


   

<span id="ERROR_LOG_RESIZE_INVALID_SIZE"></span><span id="error_log_resize_invalid_size"></span>**ERROR\_LOG\_RESIZE\_INVALID\_SIZE**
   

6806 (0x1A96)
 



The requested log size is invalid.


   

<span id="ERROR_OBJECT_NO_LONGER_EXISTS"></span><span id="error_object_no_longer_exists"></span>**ERROR\_OBJECT\_NO\_LONGER\_EXISTS**
   

6807 (0x1A97)
 



The object (file, stream, link) corresponding to the handle has been deleted by a Transaction Savepoint Rollback.


   

<span id="ERROR_STREAM_MINIVERSION_NOT_FOUND"></span><span id="error_stream_miniversion_not_found"></span>**ERROR\_STREAM\_MINIVERSION\_NOT\_FOUND**
   

6808 (0x1A98)
 



The specified file miniversion was not found for this transacted file open.


   

<span id="ERROR_STREAM_MINIVERSION_NOT_VALID"></span><span id="error_stream_miniversion_not_valid"></span>**ERROR\_STREAM\_MINIVERSION\_NOT\_VALID**
   

6809 (0x1A99)
 



The specified file miniversion was found but has been invalidated. Most likely cause is a transaction savepoint rollback.


   

<span id="ERROR_MINIVERSION_INACCESSIBLE_FROM_SPECIFIED_TRANSACTION"></span><span id="error_miniversion_inaccessible_from_specified_transaction"></span>**ERROR\_MINIVERSION\_INACCESSIBLE\_FROM\_SPECIFIED\_TRANSACTION**
   

6810 (0x1A9A)
 



A miniversion may only be opened in the context of the transaction that created it.


   

<span id="ERROR_CANT_OPEN_MINIVERSION_WITH_MODIFY_INTENT"></span><span id="error_cant_open_miniversion_with_modify_intent"></span>**ERROR\_CANT\_OPEN\_MINIVERSION\_WITH\_MODIFY\_INTENT**
   

6811 (0x1A9B)
 



It is not possible to open a miniversion with modify access.


   

<span id="ERROR_CANT_CREATE_MORE_STREAM_MINIVERSIONS"></span><span id="error_cant_create_more_stream_miniversions"></span>**ERROR\_CANT\_CREATE\_MORE\_STREAM\_MINIVERSIONS**
   

6812 (0x1A9C)
 



It is not possible to create any more miniversions for this stream.


   

<span id="ERROR_REMOTE_FILE_VERSION_MISMATCH"></span><span id="error_remote_file_version_mismatch"></span>**ERROR\_REMOTE\_FILE\_VERSION\_MISMATCH**
   

6814 (0x1A9E)
 



The remote server sent mismatching version number or Fid for a file opened with transactions.


   

<span id="ERROR_HANDLE_NO_LONGER_VALID"></span><span id="error_handle_no_longer_valid"></span>**ERROR\_HANDLE\_NO\_LONGER\_VALID**
   

6815 (0x1A9F)
 



The handle has been invalidated by a transaction. The most likely cause is the presence of memory mapping on a file or an open handle when the transaction ended or rolled back to savepoint.


   

<span id="ERROR_NO_TXF_METADATA"></span><span id="error_no_txf_metadata"></span>**ERROR\_NO\_TXF\_METADATA**
   

6816 (0x1AA0)
 



There is no transaction metadata on the file.


   

<span id="ERROR_LOG_CORRUPTION_DETECTED"></span><span id="error_log_corruption_detected"></span>**ERROR\_LOG\_CORRUPTION\_DETECTED**
   

6817 (0x1AA1)
 



The log data is corrupt.


   

<span id="ERROR_CANT_RECOVER_WITH_HANDLE_OPEN"></span><span id="error_cant_recover_with_handle_open"></span>**ERROR\_CANT\_RECOVER\_WITH\_HANDLE\_OPEN**
   

6818 (0x1AA2)
 



The file can't be recovered because there is a handle still open on it.


   

<span id="ERROR_RM_DISCONNECTED"></span><span id="error_rm_disconnected"></span>**ERROR\_RM\_DISCONNECTED**
   

6819 (0x1AA3)
 



The transaction outcome is unavailable because the resource manager responsible for it has disconnected.


   

<span id="ERROR_ENLISTMENT_NOT_SUPERIOR"></span><span id="error_enlistment_not_superior"></span>**ERROR\_ENLISTMENT\_NOT\_SUPERIOR**
   

6820 (0x1AA4)
 



The request was rejected because the enlistment in question is not a superior enlistment.


   

<span id="ERROR_RECOVERY_NOT_NEEDED"></span><span id="error_recovery_not_needed"></span>**ERROR\_RECOVERY\_NOT\_NEEDED**
   

6821 (0x1AA5)
 



The transactional resource manager is already consistent. Recovery is not needed.


   

<span id="ERROR_RM_ALREADY_STARTED"></span><span id="error_rm_already_started"></span>**ERROR\_RM\_ALREADY\_STARTED**
   

6822 (0x1AA6)
 



The transactional resource manager has already been started.


   

<span id="ERROR_FILE_IDENTITY_NOT_PERSISTENT"></span><span id="error_file_identity_not_persistent"></span>**ERROR\_FILE\_IDENTITY\_NOT\_PERSISTENT**
   

6823 (0x1AA7)
 



The file cannot be opened transactionally, because its identity depends on the outcome of an unresolved transaction.


   

<span id="ERROR_CANT_BREAK_TRANSACTIONAL_DEPENDENCY"></span><span id="error_cant_break_transactional_dependency"></span>**ERROR\_CANT\_BREAK\_TRANSACTIONAL\_DEPENDENCY**
   

6824 (0x1AA8)
 



The operation cannot be performed because another transaction is depending on the fact that this property will not change.


   

<span id="ERROR_CANT_CROSS_RM_BOUNDARY"></span><span id="error_cant_cross_rm_boundary"></span>**ERROR\_CANT\_CROSS\_RM\_BOUNDARY**
   

6825 (0x1AA9)
 



The operation would involve a single file with two transactional resource managers and is therefore not allowed.


   

<span id="ERROR_TXF_DIR_NOT_EMPTY"></span><span id="error_txf_dir_not_empty"></span>**ERROR\_TXF\_DIR\_NOT\_EMPTY**
   

6826 (0x1AAA)
 



The $Txf directory must be empty for this operation to succeed.


   

<span id="ERROR_INDOUBT_TRANSACTIONS_EXIST"></span><span id="error_indoubt_transactions_exist"></span>**ERROR\_INDOUBT\_TRANSACTIONS\_EXIST**
   

6827 (0x1AAB)
 



The operation would leave a transactional resource manager in an inconsistent state and is therefore not allowed.


   

<span id="ERROR_TM_VOLATILE"></span><span id="error_tm_volatile"></span>**ERROR\_TM\_VOLATILE**
   

6828 (0x1AAC)
 



The operation could not be completed because the transaction manager does not have a log.


   

<span id="ERROR_ROLLBACK_TIMER_EXPIRED"></span><span id="error_rollback_timer_expired"></span>**ERROR\_ROLLBACK\_TIMER\_EXPIRED**
   

6829 (0x1AAD)
 



A rollback could not be scheduled because a previously scheduled rollback has already executed or been queued for execution.


   

<span id="ERROR_TXF_ATTRIBUTE_CORRUPT"></span><span id="error_txf_attribute_corrupt"></span>**ERROR\_TXF\_ATTRIBUTE\_CORRUPT**
   

6830 (0x1AAE)
 



The transactional metadata attribute on the file or directory is corrupt and unreadable.


   

<span id="ERROR_EFS_NOT_ALLOWED_IN_TRANSACTION"></span><span id="error_efs_not_allowed_in_transaction"></span>**ERROR\_EFS\_NOT\_ALLOWED\_IN\_TRANSACTION**
   

6831 (0x1AAF)
 



The encryption operation could not be completed because a transaction is active.


   

<span id="ERROR_TRANSACTIONAL_OPEN_NOT_ALLOWED"></span><span id="error_transactional_open_not_allowed"></span>**ERROR\_TRANSACTIONAL\_OPEN\_NOT\_ALLOWED**
   

6832 (0x1AB0)
 



This object is not allowed to be opened in a transaction.


   

<span id="ERROR_LOG_GROWTH_FAILED"></span><span id="error_log_growth_failed"></span>**ERROR\_LOG\_GROWTH\_FAILED**
   

6833 (0x1AB1)
 



An attempt to create space in the transactional resource manager's log failed. The failure status has been recorded in the event log.


   

<span id="ERROR_TRANSACTED_MAPPING_UNSUPPORTED_REMOTE"></span><span id="error_transacted_mapping_unsupported_remote"></span>**ERROR\_TRANSACTED\_MAPPING\_UNSUPPORTED\_REMOTE**
   

6834 (0x1AB2)
 



Memory mapping (creating a mapped section) a remote file under a transaction is not supported.


   

<span id="ERROR_TXF_METADATA_ALREADY_PRESENT"></span><span id="error_txf_metadata_already_present"></span>**ERROR\_TXF\_METADATA\_ALREADY\_PRESENT**
   

6835 (0x1AB3)
 



Transaction metadata is already present on this file and cannot be superseded.


   

<span id="ERROR_TRANSACTION_SCOPE_CALLBACKS_NOT_SET"></span><span id="error_transaction_scope_callbacks_not_set"></span>**ERROR\_TRANSACTION\_SCOPE\_CALLBACKS\_NOT\_SET**
   

6836 (0x1AB4)
 



A transaction scope could not be entered because the scope handler has not been initialized.


   

<span id="ERROR_TRANSACTION_REQUIRED_PROMOTION"></span><span id="error_transaction_required_promotion"></span>**ERROR\_TRANSACTION\_REQUIRED\_PROMOTION**
   

6837 (0x1AB5)
 



Promotion was required in order to allow the resource manager to enlist, but the transaction was set to disallow it.


   

<span id="ERROR_CANNOT_EXECUTE_FILE_IN_TRANSACTION"></span><span id="error_cannot_execute_file_in_transaction"></span>**ERROR\_CANNOT\_EXECUTE\_FILE\_IN\_TRANSACTION**
   

6838 (0x1AB6)
 



This file is open for modification in an unresolved transaction and may be opened for execute only by a transacted reader.


   

<span id="ERROR_TRANSACTIONS_NOT_FROZEN"></span><span id="error_transactions_not_frozen"></span>**ERROR\_TRANSACTIONS\_NOT\_FROZEN**
   

6839 (0x1AB7)
 



The request to thaw frozen transactions was ignored because transactions had not previously been frozen.


   

<span id="ERROR_TRANSACTION_FREEZE_IN_PROGRESS"></span><span id="error_transaction_freeze_in_progress"></span>**ERROR\_TRANSACTION\_FREEZE\_IN\_PROGRESS**
   

6840 (0x1AB8)
 



Transactions cannot be frozen because a freeze is already in progress.


   

<span id="ERROR_NOT_SNAPSHOT_VOLUME"></span><span id="error_not_snapshot_volume"></span>**ERROR\_NOT\_SNAPSHOT\_VOLUME**
   

6841 (0x1AB9)
 



The target volume is not a snapshot volume. This operation is only valid on a volume mounted as a snapshot.


   

<span id="ERROR_NO_SAVEPOINT_WITH_OPEN_FILES"></span><span id="error_no_savepoint_with_open_files"></span>**ERROR\_NO\_SAVEPOINT\_WITH\_OPEN\_FILES**
   

6842 (0x1ABA)
 



The savepoint operation failed because files are open on the transaction. This is not permitted.


   

<span id="ERROR_DATA_LOST_REPAIR"></span><span id="error_data_lost_repair"></span>**ERROR\_DATA\_LOST\_REPAIR**
   

6843 (0x1ABB)
 



Windows has discovered corruption in a file, and that file has since been repaired. Data loss may have occurred.


   

<span id="ERROR_SPARSE_NOT_ALLOWED_IN_TRANSACTION"></span><span id="error_sparse_not_allowed_in_transaction"></span>**ERROR\_SPARSE\_NOT\_ALLOWED\_IN\_TRANSACTION**
   

6844 (0x1ABC)
 



The sparse operation could not be completed because a transaction is active on the file.


   

<span id="ERROR_TM_IDENTITY_MISMATCH"></span><span id="error_tm_identity_mismatch"></span>**ERROR\_TM\_IDENTITY\_MISMATCH**
   

6845 (0x1ABD)
 



The call to create a TransactionManager object failed because the Tm Identity stored in the logfile does not match the Tm Identity that was passed in as an argument.


   

<span id="ERROR_FLOATED_SECTION"></span><span id="error_floated_section"></span>**ERROR\_FLOATED\_SECTION**
   

6846 (0x1ABE)
 



I/O was attempted on a section object that has been floated as a result of a transaction ending. There is no valid data.


   

<span id="ERROR_CANNOT_ACCEPT_TRANSACTED_WORK"></span><span id="error_cannot_accept_transacted_work"></span>**ERROR\_CANNOT\_ACCEPT\_TRANSACTED\_WORK**
   

6847 (0x1ABF)
 



The transactional resource manager cannot currently accept transacted work due to a transient condition such as low resources.


   

<span id="ERROR_CANNOT_ABORT_TRANSACTIONS"></span><span id="error_cannot_abort_transactions"></span>**ERROR\_CANNOT\_ABORT\_TRANSACTIONS**
   

6848 (0x1AC0)
 



The transactional resource manager had too many tranactions outstanding that could not be aborted. The transactional resource manger has been shut down.


   

<span id="ERROR_BAD_CLUSTERS"></span><span id="error_bad_clusters"></span>**ERROR\_BAD\_CLUSTERS**
   

6849 (0x1AC1)
 



The operation could not be completed due to bad clusters on disk.


   

<span id="ERROR_COMPRESSION_NOT_ALLOWED_IN_TRANSACTION"></span><span id="error_compression_not_allowed_in_transaction"></span>**ERROR\_COMPRESSION\_NOT\_ALLOWED\_IN\_TRANSACTION**
   

6850 (0x1AC2)
 



The compression operation could not be completed because a transaction is active on the file.


   

<span id="ERROR_VOLUME_DIRTY"></span><span id="error_volume_dirty"></span>**ERROR\_VOLUME\_DIRTY**
   

6851 (0x1AC3)
 



The operation could not be completed because the volume is dirty. Please run chkdsk and try again.


   

<span id="ERROR_NO_LINK_TRACKING_IN_TRANSACTION"></span><span id="error_no_link_tracking_in_transaction"></span>**ERROR\_NO\_LINK\_TRACKING\_IN\_TRANSACTION**
   

6852 (0x1AC4)
 



The link tracking operation could not be completed because a transaction is active.


   

<span id="ERROR_OPERATION_NOT_SUPPORTED_IN_TRANSACTION"></span><span id="error_operation_not_supported_in_transaction"></span>**ERROR\_OPERATION\_NOT\_SUPPORTED\_IN\_TRANSACTION**
   

6853 (0x1AC5)
 



This operation cannot be performed in a transaction.


   

<span id="ERROR_EXPIRED_HANDLE"></span><span id="error_expired_handle"></span>**ERROR\_EXPIRED\_HANDLE**
   

6854 (0x1AC6)
 



The handle is no longer properly associated with its transaction. It may have been opened in a transactional resource manager that was subsequently forced to restart. Please close the handle and open a new one.


   

<span id="ERROR_TRANSACTION_NOT_ENLISTED"></span><span id="error_transaction_not_enlisted"></span>**ERROR\_TRANSACTION\_NOT\_ENLISTED**
   

6855 (0x1AC7)
 



The specified operation could not be performed because the resource manager is not enlisted in the transaction.


   

<span id="ERROR_CTX_WINSTATION_NAME_INVALID"></span><span id="error_ctx_winstation_name_invalid"></span>**ERROR\_CTX\_WINSTATION\_NAME\_INVALID**
   

7001 (0x1B59)
 



The specified session name is invalid.


   

<span id="ERROR_CTX_INVALID_PD"></span><span id="error_ctx_invalid_pd"></span>**ERROR\_CTX\_INVALID\_PD**
   

7002 (0x1B5A)
 



The specified protocol driver is invalid.


   

<span id="ERROR_CTX_PD_NOT_FOUND"></span><span id="error_ctx_pd_not_found"></span>**ERROR\_CTX\_PD\_NOT\_FOUND**
   

7003 (0x1B5B)
 



The specified protocol driver was not found in the system path.


   

<span id="ERROR_CTX_WD_NOT_FOUND"></span><span id="error_ctx_wd_not_found"></span>**ERROR\_CTX\_WD\_NOT\_FOUND**
   

7004 (0x1B5C)
 



The specified terminal connection driver was not found in the system path.


   

<span id="ERROR_CTX_CANNOT_MAKE_EVENTLOG_ENTRY"></span><span id="error_ctx_cannot_make_eventlog_entry"></span>**ERROR\_CTX\_CANNOT\_MAKE\_EVENTLOG\_ENTRY**
   

7005 (0x1B5D)
 



A registry key for event logging could not be created for this session.


   

<span id="ERROR_CTX_SERVICE_NAME_COLLISION"></span><span id="error_ctx_service_name_collision"></span>**ERROR\_CTX\_SERVICE\_NAME\_COLLISION**
   

7006 (0x1B5E)
 



A service with the same name already exists on the system.


   

<span id="ERROR_CTX_CLOSE_PENDING"></span><span id="error_ctx_close_pending"></span>**ERROR\_CTX\_CLOSE\_PENDING**
   

7007 (0x1B5F)
 



A close operation is pending on the session.


   

<span id="ERROR_CTX_NO_OUTBUF"></span><span id="error_ctx_no_outbuf"></span>**ERROR\_CTX\_NO\_OUTBUF**
   

7008 (0x1B60)
 



There are no free output buffers available.


   

<span id="ERROR_CTX_MODEM_INF_NOT_FOUND"></span><span id="error_ctx_modem_inf_not_found"></span>**ERROR\_CTX\_MODEM\_INF\_NOT\_FOUND**
   

7009 (0x1B61)
 



The MODEM.INF file was not found.


   

<span id="ERROR_CTX_INVALID_MODEMNAME"></span><span id="error_ctx_invalid_modemname"></span>**ERROR\_CTX\_INVALID\_MODEMNAME**
   

7010 (0x1B62)
 



The modem name was not found in MODEM.INF.


   

<span id="ERROR_CTX_MODEM_RESPONSE_ERROR"></span><span id="error_ctx_modem_response_error"></span>**ERROR\_CTX\_MODEM\_RESPONSE\_ERROR**
   

7011 (0x1B63)
 



The modem did not accept the command sent to it. Verify that the configured modem name matches the attached modem.


   

<span id="ERROR_CTX_MODEM_RESPONSE_TIMEOUT"></span><span id="error_ctx_modem_response_timeout"></span>**ERROR\_CTX\_MODEM\_RESPONSE\_TIMEOUT**
   

7012 (0x1B64)
 



The modem did not respond to the command sent to it. Verify that the modem is properly cabled and powered on.


   

<span id="ERROR_CTX_MODEM_RESPONSE_NO_CARRIER"></span><span id="error_ctx_modem_response_no_carrier"></span>**ERROR\_CTX\_MODEM\_RESPONSE\_NO\_CARRIER**
   

7013 (0x1B65)
 



Carrier detect has failed or carrier has been dropped due to disconnect.


   

<span id="ERROR_CTX_MODEM_RESPONSE_NO_DIALTONE"></span><span id="error_ctx_modem_response_no_dialtone"></span>**ERROR\_CTX\_MODEM\_RESPONSE\_NO\_DIALTONE**
   

7014 (0x1B66)
 



Dial tone not detected within the required time. Verify that the phone cable is properly attached and functional.


   

<span id="ERROR_CTX_MODEM_RESPONSE_BUSY"></span><span id="error_ctx_modem_response_busy"></span>**ERROR\_CTX\_MODEM\_RESPONSE\_BUSY**
   

7015 (0x1B67)
 



Busy signal detected at remote site on callback.


   

<span id="ERROR_CTX_MODEM_RESPONSE_VOICE"></span><span id="error_ctx_modem_response_voice"></span>**ERROR\_CTX\_MODEM\_RESPONSE\_VOICE**
   

7016 (0x1B68)
 



Voice detected at remote site on callback.


   

<span id="ERROR_CTX_TD_ERROR"></span><span id="error_ctx_td_error"></span>**ERROR\_CTX\_TD\_ERROR**
   

7017 (0x1B69)
 



Transport driver error.


   

<span id="ERROR_CTX_WINSTATION_NOT_FOUND"></span><span id="error_ctx_winstation_not_found"></span>**ERROR\_CTX\_WINSTATION\_NOT\_FOUND**
   

7022 (0x1B6E)
 



The specified session cannot be found.


   

<span id="ERROR_CTX_WINSTATION_ALREADY_EXISTS"></span><span id="error_ctx_winstation_already_exists"></span>**ERROR\_CTX\_WINSTATION\_ALREADY\_EXISTS**
   

7023 (0x1B6F)
 



The specified session name is already in use.


   

<span id="ERROR_CTX_WINSTATION_BUSY"></span><span id="error_ctx_winstation_busy"></span>**ERROR\_CTX\_WINSTATION\_BUSY**
   

7024 (0x1B70)
 



The task you are trying to do can't be completed because Remote Desktop Services is currently busy. Please try again in a few minutes. Other users should still be able to log on.


   

<span id="ERROR_CTX_BAD_VIDEO_MODE"></span><span id="error_ctx_bad_video_mode"></span>**ERROR\_CTX\_BAD\_VIDEO\_MODE**
   

7025 (0x1B71)
 



An attempt has been made to connect to a session whose video mode is not supported by the current client.


   

<span id="ERROR_CTX_GRAPHICS_INVALID"></span><span id="error_ctx_graphics_invalid"></span>**ERROR\_CTX\_GRAPHICS\_INVALID**
   

7035 (0x1B7B)
 



The application attempted to enable DOS graphics mode. DOS graphics mode is not supported.


   

<span id="ERROR_CTX_LOGON_DISABLED"></span><span id="error_ctx_logon_disabled"></span>**ERROR\_CTX\_LOGON\_DISABLED**
   

7037 (0x1B7D)
 



Your interactive logon privilege has been disabled. Please contact your administrator.


   

<span id="ERROR_CTX_NOT_CONSOLE"></span><span id="error_ctx_not_console"></span>**ERROR\_CTX\_NOT\_CONSOLE**
   

7038 (0x1B7E)
 



The requested operation can be performed only on the system console. This is most often the result of a driver or system DLL requiring direct console access.


   

<span id="ERROR_CTX_CLIENT_QUERY_TIMEOUT"></span><span id="error_ctx_client_query_timeout"></span>**ERROR\_CTX\_CLIENT\_QUERY\_TIMEOUT**
   

7040 (0x1B80)
 



The client failed to respond to the server connect message.


   

<span id="ERROR_CTX_CONSOLE_DISCONNECT"></span><span id="error_ctx_console_disconnect"></span>**ERROR\_CTX\_CONSOLE\_DISCONNECT**
   

7041 (0x1B81)
 



Disconnecting the console session is not supported.


   

<span id="ERROR_CTX_CONSOLE_CONNECT"></span><span id="error_ctx_console_connect"></span>**ERROR\_CTX\_CONSOLE\_CONNECT**
   

7042 (0x1B82)
 



Reconnecting a disconnected session to the console is not supported.


   

<span id="ERROR_CTX_SHADOW_DENIED"></span><span id="error_ctx_shadow_denied"></span>**ERROR\_CTX\_SHADOW\_DENIED**
   

7044 (0x1B84)
 



The request to control another session remotely was denied.


   

<span id="ERROR_CTX_WINSTATION_ACCESS_DENIED"></span><span id="error_ctx_winstation_access_denied"></span>**ERROR\_CTX\_WINSTATION\_ACCESS\_DENIED**
   

7045 (0x1B85)
 



The requested session access is denied.


   

<span id="ERROR_CTX_INVALID_WD"></span><span id="error_ctx_invalid_wd"></span>**ERROR\_CTX\_INVALID\_WD**
   

7049 (0x1B89)
 



The specified terminal connection driver is invalid.


   

<span id="ERROR_CTX_SHADOW_INVALID"></span><span id="error_ctx_shadow_invalid"></span>**ERROR\_CTX\_SHADOW\_INVALID**
   

7050 (0x1B8A)
 



The requested session cannot be controlled remotely. This may be because the session is disconnected or does not currently have a user logged on.


   

<span id="ERROR_CTX_SHADOW_DISABLED"></span><span id="error_ctx_shadow_disabled"></span>**ERROR\_CTX\_SHADOW\_DISABLED**
   

7051 (0x1B8B)
 



The requested session is not configured to allow remote control.


   

<span id="ERROR_CTX_CLIENT_LICENSE_IN_USE"></span><span id="error_ctx_client_license_in_use"></span>**ERROR\_CTX\_CLIENT\_LICENSE\_IN\_USE**
   

7052 (0x1B8C)
 



Your request to connect to this Terminal Server has been rejected. Your Terminal Server client license number is currently being used by another user. Please call your system administrator to obtain a unique license number.


   

<span id="ERROR_CTX_CLIENT_LICENSE_NOT_SET"></span><span id="error_ctx_client_license_not_set"></span>**ERROR\_CTX\_CLIENT\_LICENSE\_NOT\_SET**
   

7053 (0x1B8D)
 



Your request to connect to this Terminal Server has been rejected. Your Terminal Server client license number has not been entered for this copy of the Terminal Server client. Please contact your system administrator.


   

<span id="ERROR_CTX_LICENSE_NOT_AVAILABLE"></span><span id="error_ctx_license_not_available"></span>**ERROR\_CTX\_LICENSE\_NOT\_AVAILABLE**
   

7054 (0x1B8E)
 



The number of connections to this computer is limited and all connections are in use right now. Try connecting later or contact your system administrator.


   

<span id="ERROR_CTX_LICENSE_CLIENT_INVALID"></span><span id="error_ctx_license_client_invalid"></span>**ERROR\_CTX\_LICENSE\_CLIENT\_INVALID**
   

7055 (0x1B8F)
 



The client you are using is not licensed to use this system. Your logon request is denied.


   

<span id="ERROR_CTX_LICENSE_EXPIRED"></span><span id="error_ctx_license_expired"></span>**ERROR\_CTX\_LICENSE\_EXPIRED**
   

7056 (0x1B90)
 



The system license has expired. Your logon request is denied.


   

<span id="ERROR_CTX_SHADOW_NOT_RUNNING"></span><span id="error_ctx_shadow_not_running"></span>**ERROR\_CTX\_SHADOW\_NOT\_RUNNING**
   

7057 (0x1B91)
 



Remote control could not be terminated because the specified session is not currently being remotely controlled.


   

<span id="ERROR_CTX_SHADOW_ENDED_BY_MODE_CHANGE"></span><span id="error_ctx_shadow_ended_by_mode_change"></span>**ERROR\_CTX\_SHADOW\_ENDED\_BY\_MODE\_CHANGE**
   

7058 (0x1B92)
 



The remote control of the console was terminated because the display mode was changed. Changing the display mode in a remote control session is not supported.


   

<span id="ERROR_ACTIVATION_COUNT_EXCEEDED"></span><span id="error_activation_count_exceeded"></span>**ERROR\_ACTIVATION\_COUNT\_EXCEEDED**
   

7059 (0x1B93)
 



Activation has already been reset the maximum number of times for this installation. Your activation timer will not be cleared.


   

<span id="ERROR_CTX_WINSTATIONS_DISABLED"></span><span id="error_ctx_winstations_disabled"></span>**ERROR\_CTX\_WINSTATIONS\_DISABLED**
   

7060 (0x1B94)
 



Remote logins are currently disabled.


   

<span id="ERROR_CTX_ENCRYPTION_LEVEL_REQUIRED"></span><span id="error_ctx_encryption_level_required"></span>**ERROR\_CTX\_ENCRYPTION\_LEVEL\_REQUIRED**
   

7061 (0x1B95)
 



You do not have the proper encryption level to access this Session.


   

<span id="ERROR_CTX_SESSION_IN_USE"></span><span id="error_ctx_session_in_use"></span>**ERROR\_CTX\_SESSION\_IN\_USE**
   

7062 (0x1B96)
 



The user %s\\\\%s is currently logged on to this computer. Only the current user or an administrator can log on to this computer.


   

<span id="ERROR_CTX_NO_FORCE_LOGOFF"></span><span id="error_ctx_no_force_logoff"></span>**ERROR\_CTX\_NO\_FORCE\_LOGOFF**
   

7063 (0x1B97)
 



The user %s\\\\%s is already logged on to the console of this computer. You do not have permission to log in at this time. To resolve this issue, contact %s\\\\%s and have them log off.


   

<span id="ERROR_CTX_ACCOUNT_RESTRICTION"></span><span id="error_ctx_account_restriction"></span>**ERROR\_CTX\_ACCOUNT\_RESTRICTION**
   

7064 (0x1B98)
 



Unable to log you on because of an account restriction.


   

<span id="ERROR_RDP_PROTOCOL_ERROR"></span><span id="error_rdp_protocol_error"></span>**ERROR\_RDP\_PROTOCOL\_ERROR**
   

7065 (0x1B99)
 



The RDP protocol component %2 detected an error in the protocol stream and has disconnected the client.


   

<span id="ERROR_CTX_CDM_CONNECT"></span><span id="error_ctx_cdm_connect"></span>**ERROR\_CTX\_CDM\_CONNECT**
   

7066 (0x1B9A)
 



The Client Drive Mapping Service Has Connected on Terminal Connection.


   

<span id="ERROR_CTX_CDM_DISCONNECT"></span><span id="error_ctx_cdm_disconnect"></span>**ERROR\_CTX\_CDM\_DISCONNECT**
   

7067 (0x1B9B)
 



The Client Drive Mapping Service Has Disconnected on Terminal Connection.


   

<span id="ERROR_CTX_SECURITY_LAYER_ERROR"></span><span id="error_ctx_security_layer_error"></span>**ERROR\_CTX\_SECURITY\_LAYER\_ERROR**
   

7068 (0x1B9C)
 



The Terminal Server security layer detected an error in the protocol stream and has disconnected the client.


   

<span id="ERROR_TS_INCOMPATIBLE_SESSIONS"></span><span id="error_ts_incompatible_sessions"></span>**ERROR\_TS\_INCOMPATIBLE\_SESSIONS**
   

7069 (0x1B9D)
 



The target session is incompatible with the current session.


   

<span id="ERROR_TS_VIDEO_SUBSYSTEM_ERROR"></span><span id="error_ts_video_subsystem_error"></span>**ERROR\_TS\_VIDEO\_SUBSYSTEM\_ERROR**
   

7070 (0x1B9E)
 



Windows can't connect to your session because a problem occurred in the Windows video subsystem. Try connecting again later, or contact the server administrator for assistance.


   

<span id="FRS_ERR_INVALID_API_SEQUENCE"></span><span id="frs_err_invalid_api_sequence"></span>**FRS\_ERR\_INVALID\_API\_SEQUENCE**
   

8001 (0x1F41)
 



The file replication service API was called incorrectly.


   

<span id="FRS_ERR_STARTING_SERVICE"></span><span id="frs_err_starting_service"></span>**FRS\_ERR\_STARTING\_SERVICE**
   

8002 (0x1F42)
 



The file replication service cannot be started.


   

<span id="FRS_ERR_STOPPING_SERVICE"></span><span id="frs_err_stopping_service"></span>**FRS\_ERR\_STOPPING\_SERVICE**
   

8003 (0x1F43)
 



The file replication service cannot be stopped.


   

<span id="FRS_ERR_INTERNAL_API"></span><span id="frs_err_internal_api"></span>**FRS\_ERR\_INTERNAL\_API**
   

8004 (0x1F44)
 



The file replication service API terminated the request. The event log may have more information.


   

<span id="FRS_ERR_INTERNAL"></span><span id="frs_err_internal"></span>**FRS\_ERR\_INTERNAL**
   

8005 (0x1F45)
 



The file replication service terminated the request. The event log may have more information.


   

<span id="FRS_ERR_SERVICE_COMM"></span><span id="frs_err_service_comm"></span>**FRS\_ERR\_SERVICE\_COMM**
   

8006 (0x1F46)
 



The file replication service cannot be contacted. The event log may have more information.


   

<span id="FRS_ERR_INSUFFICIENT_PRIV"></span><span id="frs_err_insufficient_priv"></span>**FRS\_ERR\_INSUFFICIENT\_PRIV**
   

8007 (0x1F47)
 



The file replication service cannot satisfy the request because the user has insufficient privileges. The event log may have more information.


   

<span id="FRS_ERR_AUTHENTICATION"></span><span id="frs_err_authentication"></span>**FRS\_ERR\_AUTHENTICATION**
   

8008 (0x1F48)
 



The file replication service cannot satisfy the request because authenticated RPC is not available. The event log may have more information.


   

<span id="FRS_ERR_PARENT_INSUFFICIENT_PRIV"></span><span id="frs_err_parent_insufficient_priv"></span>**FRS\_ERR\_PARENT\_INSUFFICIENT\_PRIV**
   

8009 (0x1F49)
 



The file replication service cannot satisfy the request because the user has insufficient privileges on the domain controller. The event log may have more information.


   

<span id="FRS_ERR_PARENT_AUTHENTICATION"></span><span id="frs_err_parent_authentication"></span>**FRS\_ERR\_PARENT\_AUTHENTICATION**
   

8010 (0x1F4A)
 



The file replication service cannot satisfy the request because authenticated RPC is not available on the domain controller. The event log may have more information.


   

<span id="FRS_ERR_CHILD_TO_PARENT_COMM"></span><span id="frs_err_child_to_parent_comm"></span>**FRS\_ERR\_CHILD\_TO\_PARENT\_COMM**
   

8011 (0x1F4B)
 



The file replication service cannot communicate with the file replication service on the domain controller. The event log may have more information.


   

<span id="FRS_ERR_PARENT_TO_CHILD_COMM"></span><span id="frs_err_parent_to_child_comm"></span>**FRS\_ERR\_PARENT\_TO\_CHILD\_COMM**
   

8012 (0x1F4C)
 



The file replication service on the domain controller cannot communicate with the file replication service on this computer. The event log may have more information.


   

<span id="FRS_ERR_SYSVOL_POPULATE"></span><span id="frs_err_sysvol_populate"></span>**FRS\_ERR\_SYSVOL\_POPULATE**
   

8013 (0x1F4D)
 



The file replication service cannot populate the system volume because of an internal error. The event log may have more information.


   

<span id="FRS_ERR_SYSVOL_POPULATE_TIMEOUT"></span><span id="frs_err_sysvol_populate_timeout"></span>**FRS\_ERR\_SYSVOL\_POPULATE\_TIMEOUT**
   

8014 (0x1F4E)
 



The file replication service cannot populate the system volume because of an internal timeout. The event log may have more information.


   

<span id="FRS_ERR_SYSVOL_IS_BUSY"></span><span id="frs_err_sysvol_is_busy"></span>**FRS\_ERR\_SYSVOL\_IS\_BUSY**
   

8015 (0x1F4F)
 



The file replication service cannot process the request. The system volume is busy with a previous request.


   

<span id="FRS_ERR_SYSVOL_DEMOTE"></span><span id="frs_err_sysvol_demote"></span>**FRS\_ERR\_SYSVOL\_DEMOTE**
   

8016 (0x1F50)
 



The file replication service cannot stop replicating the system volume because of an internal error. The event log may have more information.


   

<span id="FRS_ERR_INVALID_SERVICE_PARAMETER"></span><span id="frs_err_invalid_service_parameter"></span>**FRS\_ERR\_INVALID\_SERVICE\_PARAMETER**
   

8017 (0x1F51)
 



The file replication service detected an invalid parameter.


   

## Requirements



| Requirement | Value |
|-------------------------------------|---------------------------------------------------------------------------------------|
| Minimum supported client<br/> | Windows XP \[desktop apps only\]<br/>                                           |
| Minimum supported server<br/> | Windows Server 2003 \[desktop apps only\]<br/>                                  |
| Header<br/>                   |  WinError.h  |



## See also

 

[System Error Codes](system-error-codes.md)
 

 

 




