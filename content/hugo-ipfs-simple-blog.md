+++
title = "Hosting a Hugo blog in IPFS"
description = "A guide to hosting "
tags = [ "IPFS", "Hugo" ]
date = "2019-09-20"
location = "UK"
categories = [
  "Tutorials",
]
slug = "ipfs-blog-host-hugo,"
type = "post"
+++

### What is Hugo
Hugo is a static site generator which provides an quick and simple website, like this one.

### What is IPFS
IPFS (InterPlanetary File System) defines itself as ‘a peer-to-peer hypermedia protocol to make the web faster, safer, and more open.’. It is a system has been created not too dissimilar from BitTorrent, but fundamentally different in a few ways. At its core IPFS is a file-system that uses the hash of a file as the content address - As the same file will always hash to the same value, if multiple people share the same file, they are pointing at the same address, irregardless of when and where they are uploading from. it offers the world a cheap, immutable, uncensored alternative to the HTTP protocol.

### Why host a site on IPFS?
One advantage of IPFS is that it provides the opportunity for a person to create an inexpensive quick to set-up static website. In this tutorial, we will be creating a personal blog!

One of the main disadvantages currently IPFS is that it is not yet optimized enough to support more-complicated web applications. You will have to stick to lightweight static websites. This, makes it absolutely perfect to use a static site generator such as Jekyll. Here we are going to grab an existing Jekyll template, but if you would like to create your own website from scratch then feel free to skip down.


### Great! How do I start?
Well. The more personal thing would be to create your own static website. There is no server in IPFS, so if you want a more dynamic page - feel free to look into client side databases like Gun, or even [OrbitDB] - Which itself uses IPFS.

If you are looking for a no hassle, easy and quick solution, you can use Hugo as will be demonstrated in this blog. Hugo is a static site generation tool, that just requires a little tinkering and some simple commands to create a website from templates.

### Install Hugo


### Picking a theme


### Setting up the site
Firstly, in your terminal, pick a directory for your site, and run:

```
hugo new site [[folder name]]
cd [[folder name]]
```

Okay, you're now in the project root for your site. You're going to want to fine a theme

https://themes.gohugo.io/

When you've found one, follow the installation instructions in the README. 
Install the theme into the project root.

### Make some content

### Running the site

### Installing IPFS

### Deploy IPFS
