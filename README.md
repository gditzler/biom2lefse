# About 
`biom2lefse` is a script to convert a [Biom-format](http://biom-format.org/) file into one that is compatible with [LefSe](https://bitbucket.org/nsegata/lefse). The format for LefSe is different than the Biom format or the old Qiime OTU table formats. 

This software is issued under the MIT License and is provided AS IS.

# Example

```bash
git clone https://github.com/gditzler/DataCollections.git
biom2lefse -i DataCollections/Caporaso/caporaso-gut.biom -m DataCollections/Caporaso/caporaso-gut.txt -f SEX -o caporaso-lefse.txt 
```
