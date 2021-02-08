# Compress-And-Decompress
## 1.0 Details
* Its an opensource project and we did this as our third year group project.

* If it says anyfile missing then commit me i can check and attach those for use.

* All the developing files are in :compress\src\org\appache\com
For this process need to have libraries.

* Here only used appache commons compress libraries for compress and de compress the folder.
This compress and de-comress created only for zip,tar,jar,cpio formats.

## 2.0 Licence
*All the codes under the apache software licence
 **http://www.apache.org/licenses/LICENSE-2.0**
 
## 3.0 Help
 *further development use this websites 
 1. https://commons.apache.org/proper/commons-compress/
 2. https://github.com/apache/commons-vfs
 3. https://commons.apache.org/proper/commons-vfs/apidocs/org/apache/commons/vfs2/FileObject.html
 4. https://en.wikipedia.org/wiki/List_of_archive_formats
 
## 4.0 Libraries to be downloaded.
* commons-compress
* commons-long
* commons-logging
* commons-net
* commons-vfs

## 5.0 Methods
*After downloading the files put the libraries into your files
then you can call the method ,

**for compression :**
- comp.compress(source path,destination path,file type);
source path - the path the folder contain want to compress
destination path - the final place the folder need to contain after compression
file type - the compress file type (it must we zip or tar or jar or cpio )  

**for decompression :**
- comp.decompress(source path,destination path,file type);
comp.compress(source path,destination path,file type);
source path - the path the compressed folder contain
destination path - the final place the folder need to contain after decompression
file type - the compress file type (it must we zip or tar or jar or cpio)
