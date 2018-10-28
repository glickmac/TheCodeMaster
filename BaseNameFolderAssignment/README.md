## Basename Folder Creation and Assignment
The purpose of this post and script is to consolidate files into folders by the basename. In bioinformatics, I encounter situations where programs have created numerous files from an input with different extensions. When running multiple jobs these files become cluttered and difficult to move into individual folders. For example, consider the following directory structure below

**Directory**
- bar.csv
- foo.csv
- bar.tar.gz
- foo.tar.gz
- bar.txt
- foo.txt


The output of this script would convert the directory above into individually labeled folders

**Directory**

- bar

    - bar.csv
    - bar.tar.gz
    - bar.txt

- foo

    - foo.csv
    - foo.tar.gz
    - foo.txt
