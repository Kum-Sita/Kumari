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
11) false - expect(false).to.be.false
12) null - expect(null).to.be.null
13) undefined - expect(undefined).to.be.undefined
14) exist - expect(myVar).to.exist
15) empty	- expect([]).to.be.empty
16) arguments
Aliases: Arguments - expect(arguments).to.be.arguments
17) equal(value)
Aliases: equals, -  eq	expect(42).to.equal(42)
18) deep.equal(value) - expect({ name: 'Jane' }).to.deep.equal({ name: 'Jane' })
19) eql(value)
Aliases: eqls - expect({ name: 'Jane' }).to.eql({ name: 'Jane' })
20) greaterThan(value)
Aliases: gt, above	- expect(10).to.be.greaterThan(5)
21) least(value)
Aliases: gte	- expect(10).to.be.at.least(10)
22) lessThan(value)
Aliases: lt, below	- expect(5).to.be.lessThan(10)
23) most(value)
Aliases: lte - expect('test').to.have.length.of.at.most(4)
24) within(start, finish)	- expect(7).to.be.within(5,10)
25) instanceOf(constructor)
Aliases: instanceof	- expect([1, 2, 3]).to.be.instanceOf(Array)
26) property(name, [value])	- expect(obj).to.have.property('name')
27) deep.property(name, [value]) - 	expect(deepObj).to.have.deep.property('tests[1]', 'e2e')
28) ownProperty(name)
Aliases: haveOwnProperty, own.property	- expect('test').to.have.ownProperty('length')
25) ownPropertyDescriptor(name)
Aliases: haveOwnPropertyDescriptor	- expect({a: 1}).to.have.ownPropertyDescriptor('a')
26) lengthOf(value)	- expect('test').to.have.lengthOf(3)
27) match(RegExp)
Aliases: matches	- expect('testing').to.match(/^test/)
28) string(string)	- expect('testing').to.have.string('test')
29) keys(key1, [key2], [...])
Aliases: key	- expect({ pass: 1, fail: 2 }).to.have.keys('pass', 'fail')
