# Contributing to this repo
**Implementing new File/Directory Structure**
* Try to keep things as modular as possible, the new file/directory structure should be: 
```
/data_structures/general_structure/structure/language/file
ex: /data_structures/stack/char_stack/cpp/cstack/cstack.cpp cstack.h cstack.usage.cpp
/algorithms/general_algorithm/algorithm/language/file
ex: /algorithms/sort/bubble_sort/cpp/bubble_sort.cpp
```

**Old Directory Structure**
* Try to keep things as modular as possible, for example if you are creating a LinkedList data structure for cpp, if there isn't a directory already created on the root of the directory named 'cpp' then create one, inside that directory create another folder called 'linkedlist', then create your file(s) inside the linkedlist folder.

## How To:

1. `git clone https://github.com/bareinhard/Hacktoberfest-Data-Structure-and-Algorithms`
2. `git checkout -b <Your-Branch-Name-Here>`
3. Code your files in the proper directory based on the instructions above
4. add all your files `git add your/directory/path/to/file/` (see new directory structure above)
5. commit your file changes `git commit -m "Whatever you did here, e.g. created linkedlist class in C++"`
6. push your changes `git push origin <Your-Branch-Name-Here>`
7. Create a Pull Request to master

### Alternate via Web

1. Fork Repo on Web Page
2. Make your changes on your forked repo
3. Make Pull Request to master
