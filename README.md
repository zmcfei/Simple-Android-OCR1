This android project is depend on tess-two
https://github.com/rmtheis/tess-two
and 
https://github.com/GautamGupta/Simple-Android-OCR

steps 1:
   clone Simple-Android-OCR .
   2:  mkdir an directory named libraries under it.
   3. cp tess-two/tess-two into libraries.
   android studio import the whole project .]
   4: if in the new project file ,tess-two got un-changed by studio.then
             make it :ndk-build the tess-two.
			 else you should re-cp it .
   5.change the gradle of tess-two
         https://github.com/erangaeb/dev-notes/blob/master/tesseract/build.gradle
  6 .change the   buildToolsVersion "21.1.1" to your type.
  7 .make all of them.

  for more informations ,please check :https://coderwall.com/p/eurvaq/tesseract-with-andoird-and-gradle
