# UiPath
String.Join(“”, Directory.GetFiles(our_FolderPath,”*”,SearchOption.AllDirectories).OrderByDescending(Function(d) New FileInfo(d).CreationTime).Take(1) )

Note:
1.Replace our_FolderPath with your desired folder path
2.Replace “*” with your required file format “*.xlxs”,”*.pdf”…
