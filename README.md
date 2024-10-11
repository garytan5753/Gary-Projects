# Gary Tan Projects
## 1. Gary Tan Project Resume
Visit this [link](https://github.com/garytan5753/projectgtazureresume) for more details.
## 2. Using SyncADOtoGitHub Tool
I had used the [SyncADOtoGitHub](https://github.com/RekhuGopal/SyncADOtoGitHub) tool by [RekhuGopal](https://github.com/RekhuGopal). Credits to him for creating such a great tool! <br/>
However I need to make some modifiction to get the tool to work as the tool had been created a while back than. 

What I had done:

1. In the .github/workflows/ADOtoGitHubSync.yml I change the parameter `runs-on` from `windows-2019` to `windows-latest`.
2. In the same file I had change the parameter `uses` from `actions/cehckout@v2` to `actions/cehckout@v4`. If you do not change it, you will get warning when trying to running at the Actions. 
3. Change the value in ADORepoList.json according to my ADO and GitHub branch name and URL.
4. Create my GitHub PAT and ADO PAT.
5. Refer to this [video](https://www.youtube.com/watch?v=G1nKqb8be-A&t=1434s) to understand and learn more about the tool.
6. Is a manual update but it was good enough for me.

## 3. Work In Progres
