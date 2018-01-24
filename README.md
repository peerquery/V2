# V2(Only served as Proof of Concept)
Depreciated version(Proof of Concept) of Peer Query

This code was trimmed down from the v1 which had DB support and other "advanced" features. For this reason you may find random snippets of unrelated / uncompleted codes in it.


## How to run it
The site is built on Node.js and Boostrap. In the json.package file you will find all the dependiaries which are:
* express
* sitemap
* body-parser

## What you should know

**This version is only a Proof of Concept so does not include all the features for a full site.**
This site runs on Steem Connect v2 so to use it you MUST have your own Steem Connect v2 app - not account.
The code here is the **absolute** code not source code.
That means it contains **everything** that is used to run **www.peerquery.com**, logos, internal links, personal comments, everything!

## The following features work:
* Steem Connect v2 login
* Posting a post
* Voting post and comment with slidebar
* Responding/ Commenting
* Resteeming a post
* Limited users profile
* Viewing any Steem post using the permlink - not just "queries"

## What does NOT exist:
* Threaded comments
* Parsing content with Markdown parser
* Auto linking of images, profile and Youtube videos

## Lazy loading
The site is entirely client rendered - not server rendered. This means could be bad for SEO, however it is good for the server load.

Also, the navbar, sidebar and footer are loaded into "div"s by JQuery. This means that all pages share the very same single navbar, sidebar and footer.

For a Proof of Concept is, this makes the development process easier as you only edit the navbar, sidebar or footer once and the changes are applied site wide.

## Auth system
The entire Steem Connect v2 system is located in the navbar.html(which is shared on all pages). The login system is quite messy but works perfectly. It has been trimmed down from a more sophisticaed system(V1) however it still contains a few in-active code from the version 1.

## Its all yours for re-use!
Do whatever you want with it. You are responsible for whatever you do with it.

## Recommendation
The alpha version is very professional, rich in interface design(Sematic UI) and a STILL open source. If you are considering forking Peer Query, you might want play with this version to understand the workings of Peer Query and then fork the alpha for production work.
