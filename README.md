

git ls-tree -tr origin/master
https://git-scm.com/docs/git-ls-tree

git ls-remote
https://git-scm.com/docs/git-ls-remote.html

https://www.npmjs.com/package/simple-git
.listRemote([args], handlerFn)

https://stackoverflow.com/questions/4044368/what-does-treeish-mean-in-git

https://js.devexpress.com/Demos/WidgetsGallery/Demo/FileManager/BindingToFileSystem/Angular/DarkViolet/


----------------------------------------------------------------------
|    Commit-ish/Tree-ish    |                Examples
----------------------------------------------------------------------
|  1. <sha1>                | dae86e1950b1277e545cee180551750029cfe735
|  2. <describeOutput>      | v1.7.4.2-679-g3bee7fb
|  3. <refname>             | master, heads/master, refs/heads/master
|  4. <refname>@{<date>}    | master@{yesterday}, HEAD@{5 minutes ago}
|  5. <refname>@{<n>}       | master@{1}
|  6. @{<n>}                | @{1}
|  7. @{-<n>}               | @{-1}
|  8. <refname>@{upstream}  | master@{upstream}, @{u}
|  9. <rev>^                | HEAD^, v1.5.1^0
| 10. <rev>~<n>             | master~3
| 11. <rev>^{<type>}        | v0.99.8^{commit}
| 12. <rev>^{}              | v0.99.8^{}
| 13. <rev>^{/<text>}       | HEAD^{/fix nasty bug}
| 14. :/<text>              | :/fix nasty bug
----------------------------------------------------------------------
|       Tree-ish only       |                Examples
----------------------------------------------------------------------
| 15. <rev>:<path>          | HEAD:README, :README, master:./README
----------------------------------------------------------------------
|         Tree-ish?         |                Examples
----------------------------------------------------------------------
| 16. :<n>:<path>           | :0:README, :README


Interesting stuff
https://gitolite.com/gitolite/fool_proof_setup
https://gitolite.com/gitolite/vref.html
this allows for fine grained permissions.# node-git
