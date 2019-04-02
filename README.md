# AlphaFiles
### settings and parameters text files

This repo contains a directory structure of settings and parameters text files that are used by various other repos.

For windows, the files are located in C:\Alpha\Files
For linux, the files are located in /opt/alpha/files

This allows parms files to be located in a central location that has a git repo.

Here's a snippet for a parms file that is located at "/opt/alpha/files/RisLib/RisParms_Parms.txt"

``` markdown
void Parms::reset()
{
   BaseClass::reset();
   BaseClass::setFileName_RelAlphaFiles("RisLib/RisParms_Parms.txt");
}
```

