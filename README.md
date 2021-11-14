# 02-git-04-tools
##1. aefead2207ef7e2aa5dc81a34aedf0cad4c32545

`git show aefea`

##2.tag: v0.12.23

`git show 85024d3`

##3. 2 родителя
<br>56cd7859e05c36c06b56d013b55a252d0bb7e158
<br>9ea88f22fc6269854151c571162c5bcf958bee2b

`git show b8d720^1`
`git show b8d720^2`

##4. 
commit 33ff1c03bb960b332be3af2e333462dde88b279e (tag: v0.12.24)
    <br>v0.12.24

commit b14b74c4939dcab573326f4e3ee2a62e23e12f89
    <br>[Website] vmc provider links

commit 3f235065b9347a758efadc92295b540ee0a5e26e
    <br>Update CHANGELOG.md

commit 6ae64e247b332925b872447e9ce869657281c2bf
    <br>registry: Fix panic when server is unreachable
    <br>Non-HTTP errors previously resulted in a panic due to dereferencing the
    <br>resp pointer while it was nil, as part of rendering the error message.
    <br>This commit changes the error message formatting to cope with a nil
    <br>response, and extends test coverage.
    <br>Fixes #24384

commit 5c619ca1baf2e21a155fcdb4c264cc9e24a2a353
    <br>website: Remove links to the getting started guide's old location
    <br>Since these links were in the soon-to-be-deprecated 0.11 language section, I
    <br>think we can just remove them without needing to find an equivalent link.

commit 06275647e2b53d97d4f0a19a0fec11f6d69820b5
    <br>Update CHANGELOG.md

commit d5f9411f5108260320064349b757f55c09bc4b80
    <br>command: Fix bug when using terraform login on Windows

commit 4b6d06cc5dcb78af637bbb19c198faff37a066ed
    <br>Update CHANGELOG.md

commit dd01a35078f040ca984cdd349f18d0b67e486c35
    <br>Update CHANGELOG.md

commit 225466bc3e5f35baa5d07197bbc079345b77525e
    <br>Cleanup after v0.12.23 release

`git log v0.12.23..v0.12.24`

##5. commit 8c928e83589d90a031f811fae52a81be7153e82f

`git grep -p 'func providerSource(*'`
<br>`git log -L :providerSource:provider_source.go`

##6. 
78b12205587fe839f10d946ea3fdc06719decb05
<br>52dbf94834cb970b510f2fba853a5b49ad9b1a46
<br>41ab0aef7a0fe030e84018973a64135b11abcd70
<br>66ebff90cdfaa6938f26f908c7ebad8d547fea17
<br>8364383c359a6b738a436d1b7745ccdce178df47

`git grep -p 'globalPluginDirs'`
<br>`git log -L :globalPluginDirs:plugins.go`


##7. `Martin Atkins <mart@degeneration.co.uk>`

`git log -S synchronizedWriters`
<br>`git show 5ac311e2a91e381e2f52234668b49ba670aa0fe5`

