## Archive

## ZIP
  zip -r archive_name.zip folder_to_compress
  
  unzip archive_name.zip

## No hidden OS X files
`zip -r -X archive_name.zip folder_to_compress`

## TAR
`tar -zcvf archive_name.tar.gz folder_to_compress`

`tar -zxvf archive_name.tar.gz`

## BZ2
`tar -jcvf archive_name.tar.z2 folder_to_compress`

`tar -jxvf archive_name.tar.z2`

## GZ
`gunzip archivename.gz`


## DMG
(create) `hdiutil create -format UDZO -srcfolder folder_to_compress archive_name.dmg`

(mount)  `hdiutil attach archive_name.dmg`

(view)   `ls -lah /Volumes/archive_name/`

(eject)  `hdiutil eject /Volumes/archive_name/`
