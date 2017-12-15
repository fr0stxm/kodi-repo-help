# Addon repository help
---
This guide is created to help you when running your own addon; with things like setting up a repository for automatic updates. 

A lot of people struggle with setting these up; but as you'll see they are actually very simple to manage and setup. There are a number of very good YouTube videos and I recommend that you check any out that you find; I won't link any because I'm not affiliated with them. 

Things you'll need:

* A website hosting account; or somewhere you can upload files that are visible using a web browser. I recommend AntiSocial Hosting if you need hosting. *(NB. It is my own company so I would recommend it - but others will also recommend us)* - Just to be completely transparent, you can also use github (this website) but expect them to close your account.
* A decent text editor; I use [atom.io](https://atom.io) on Mac (it is available on all platforms) but you could use [Sublime](https://www.sublimetext.com/), [NotePad++](https://notepad-plus-plus.org/) or just another text editor; including Vi(m) for Linux
* Python installed on your machine or at least the ability to run Python scripts
* Kodi - of course
* The ability to run the command md5sum. Windows: [Download](http://www.pc-tools.net/win32/md5sums/) / Mac: Use brew to install `brew install md5sha1sum`

## Useful background information
### What is a repo/repository?
A repository quite simply put is a location online that contains addons or installable components for use within Kodi. This is used in conjuction with an addon itself that is declared as a repository addon that contains a detailed location of the installable components, their available versions (usually the latest) and any required additional components. 

Notice how I use the word components and not addons? This is because within a repository you can provide script modules, addons, services and skins. All of these can be referenced from the same single repository.

One of the most useful functions of a repository and its associated addon (which includes a controlling XML file) is the ability to notify anyone with your repository and components; such as an addon that an update to your addon exists and that it should update. 

Hopefully you understand this a little better now, if you have any questions, just contact me. [Twitter @IamOneil_](https://twitter.com/IamOneil_)

## Getting started

I could go through how to setup Git or your web hosting 