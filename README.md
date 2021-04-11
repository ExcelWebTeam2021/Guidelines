# Guidelines

####  Rules of Good UI Design <*MUST SEE>

* https://www.youtube.com/watch?v=34BnRBt8wOU&ab_channel=TraversyMedia
* https://www.youtube.com/watch?v=uIoatHd7GW4&ab_channel=Flux
* https://www.youtube.com/watch?v=EFf9jBs2yfU&ab_channel=SatoriGraphics
* https://www.youtube.com/watch?v=C1rQQ_YpgcI&ab_channel=TheFuturAcademy
* https://www.youtube.com/watch?v=6Q4KVKaVv9s&ab_channel=DevEd

* https://www.youtube.com/watch?v=G46m8wrXkTk&ab_channel=AdrianTwarog

## Git practises

1. https://medium.com/@immily/sampe-of-git-workflow-for-small-team-6d5836b9b7ce
2. https://deepsource.io/blog/git-best-practices/
3. Don’t git push straight to masin. Branch it out!

```
git checkout -b your-awesome-feature develop

<work on that branch>
git add *
git commit -m 'a meaningful commit'
git push

<once the feature is complete make a pull request (pr)>

someone will review the code and merge it to the master branch

NEVER DIRECTLY MERGE TO MASTER
```

3. Commit early, commit often. The commit message must be descriptive and meaningful 

- How can I keep my branch up to date with master with git?

```
Assuming you're fine with taking all of the changes in master, what you want is:

git checkout <my branch>
to switch the working tree to your branch; then:

git merge master
to merge all the changes in master with yours.
```


## Coding practise

1. UI component’s names  and variable names should be CamelCase ``` Example: LoginScreen.js ```
2. Avoid Inline CSS as and when possible
3. Be generous with comments
4. Name your files logically according to the job that they perform
5. Use a linter to make your code easier to review. Follow strict linting rules.
6. While pushing to 


### React specific

1. File- and component name need to be identical.
2. Only include one React component per file.

```javascript

// bad
<Foo className="stuff"></Foo>

// good
<Foo className="stuff" />
```

https://medium.com/@navitasinghal77/react-coding-standards-and-practices-3b133bcaea8
