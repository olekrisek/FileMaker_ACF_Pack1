# FileMaker_ACF_Pack1
General Purpose Functions for FileMaker to load/save files and some other tings. 

**Prototypes:**

=========================================================
Package: bootstrap
Functions to faciltate load and save source and binary files- Requires ACF_Plugin 1.5.1.0 as minimum. - Most functions has ACFU_\<name> equivalents. 

´´´
ACF_run("LoadFile"; text_filename)
   ==> Return type = text

ACF_run("SaveFile"; text_filename; text_content)
   ==> Return type = num

ACF_run("SelectAndGetFile"; text_startPath; text_Prompt)
   ==> Return type = text

ACF_run("SelectFolder"; text_prompt)
   ==> Return type = text

ACF_run("DirectoryExists"; text_DirectoryPath)
   ==> Return type = bool

ACF_run("GetFilenameFromPath"; text_path)
   ==> Return type = text

ACF_run("GetDirectoriesFromPath"; text_path)
   ==> Return type = text

ACF_run("GetExtentionFromPath"; text_path)
   ==> Return type = text

ACF_run("SelectFileOnly"; text_startPath; text_Prompt)
   ==> Return type = text

ACF_run("SaveFileDialogue"; text_prompt; text_proposed_folder; text_proposed_name)
   ==> Return type = text

ACF_run("OpenOutputFile"; text_path)
   ==> Return type = num

ACF_run("WriteOutputMacFileUTF8"; num_FileNo; text_data)
   ==> Return type = text

ACF_run("WriteOutputWinFileIso8859_1"; num_FileNo; text_data)
   ==> Return type = text

ACF_run("CloseFile"; num_FileNo)
   ==> Return type = text

ACF_run("WriteOutputWinFileUTF8"; num_FileNo; text_data)
   ==> Return type = text

ACF_run("NumFormat"; num_num; text_comma)
   ==> Return type = text

ACF_run("BSBO_SaveDocumentDesktop"; text_DocStore; text_ArchiveSubPath; text_Title)
   ==> Return type = text

ACF_run("GetPlatformString"; text_MacString; text_WinString)
   ==> Return type = text

ACF_run("Save_Logg"; text_logg; text_name)
   ==> Return type = text

ACF_run("Append_Logg"; text_logg; text_FilePath)
   ==> Return type = text
´´´

