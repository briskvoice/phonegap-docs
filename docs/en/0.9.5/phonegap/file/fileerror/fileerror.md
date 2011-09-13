FileError
========

A 'FileError' object is set on the FileWriter/FileReader error property when an error occurs. 

Properties
----------

- __code:__ One of the predefined error codes listed below.

Constants
---------

- `FileError.NOT_FOUND_ERR`
- `FileError.SECURITY_ERR`
- `FileError.ABORT_ERR`
- `FileError.NOT_READABLE_ERR`
- `FileError.ENCODING_ERR`
- `FileError.NO_MODIFICATION_ALLOWED_ERR`
- `FileError.INVALID_STATE_ERR`
- `FileError.SYNTAX_ERR`

Description
-----------

The `FileError` object may be thrown when an unrecoverable error occurs when reading, writing, seeking or truncating a file. When the user calls the abort method of the writer a FileError with a code of ABORT_ERR is thrown if the current state is FileWriter.DONE or FileWriter.INIT.  

