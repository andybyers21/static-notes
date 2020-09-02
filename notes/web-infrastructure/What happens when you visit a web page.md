---
layout: note
title: What happens when you visit a web page
parent: Web Infrastructure
nav_exclude: true
---

# What happens when you visit a web page
1. When you click a link or type a URL (Uniform Resource Locator)^[The URL is a way of addressing pages and resources online. (URL's will be formatted as such: *Protocol (eg, http)://Host (server)/Path( the specific location of the resource being requested*).) into your browser, the browser is matching the IP address in the DNS from your browser to the server.
2. The browser sends an HTTP request to the server, asking it to send a copy of the website to your client. This message, and all other data sent between the client and the server, is sent across your internet connection using TCP/IP.
3. If the server approves your request, the server sends the client a "200 OK" message, which means "Of course you can look at that website! Here it is", and then starts sending the website's files to your browser in a series of data packets.
4. The browser assembles the packets into a complete website and displays it to you. All this usually happens in a matter of micro-seconds. Awesome!
	