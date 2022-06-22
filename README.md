# My Git Notes

Some Frequently used Git Commands - 
- git status // for checking what changed
- git add . // to add everything to be commited
- git commit -m "YOUR COMMIT MESSAGE HERE" // To commit the changes
- git push // To push your commit(s) from local to github
- git fetch // for download contents from a remote repository
- git pull  // fetch and download content from a remote repository and immediately update the local repository to match that content
- git checkout 

For more Commands please refer - https://git-scm.com/docs/git

A good resource to commit changes to your GitHub Repo - https://www.sachinsf.com/how-to-push-the-code-from-vs-code-to-github/#:~:text=To%20push%20the%20code%20to%20GitHub%20from%20Visual,you%20have%20to%20push%20your%20folder%20to%20Github.


# My Cypress Notes 

BDD Assertions
These chainers are available for BDD assertions (expect/should). Aliases listed can be used interchangeably with their original chainer. The entire list of available BDD Chai assertions here.

Chainer-	Example
1) not	- expect(name).to.not.equal('Jane')
2) deep -	expect(obj).to.deep.equal({ name: 'Jane' })
3) nested - expect({a: {b: ['x', 'y']}}).to.have.nested.property('a.b[1]')
expect({a: {b: ['x', 'y']}}).to.nested.include({'a.b[1]': 'y'})

4) ordered	- expect([1, 2]).to.have.ordered.members([1, 2]).but.not.have.ordered.members([2, 1])
5) any	- expect(arr).to.have.any.keys('age')
6) all	- expect(arr).to.have.all.keys('name', 'age')
7) a(type)
Aliases: an	- expect('test').to.be.a('string')
8) include(value)
Aliases: contain, includes, contains - expect([1,2,3]).to.include(2)
9) ok - expect(undefined).to.not.be.ok
10) true - expect(true).to.be.true
