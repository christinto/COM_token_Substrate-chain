# COM_token_Substrate-chain
Com token substrate chain

Steps:
Install substrate. (Refer to substrate developer hub)
https://substrate.dev/docs/en/getting-started/installing-substrate
Install substrate
| => curl https://getsubstrate.io -sSf | bash

Then enter these commands below into your cli.

substrate-node-new substrate-node-template <author-name> 
  
substrate-ui-new substrate
  
This will create a folder called substrate-node-template and substrate-ui with the corresponding repositories cloned in them. You can of course rename your projects in these commands, but for the sake of the clarity, we will continue with these folder names.

Chain client created in substrate-node-template.
To start a dev chain, run:
$ substrate-node-template/target/release/substrate-node-template --dev
To create a basic Bonds UI for your chain, run:
$ substrate-ui-new substrate-node-template
To push to a newly created GitHub repository, inside substrate-node-template, run:
$ git remote add origin git@github.com:myusername/myprojectname && git push -u origin master

To start the ui, run:
$ yarn run dev

/////////////////////////////////////////////

Links:

https://substrate.dev/docs/en/tutorials/creating-your-first-substrate-chain

Node template
https://github.com/paritytech/substrate/tree/master/node-template



Getting Started on Substrate
https://docs.google.com/presentation/d/1dhaoLb5V2K_vDe4EJlUcKwePD1nMktr57fOdSo8bHns/edit#slide=id.g44a056a79b_0_206
