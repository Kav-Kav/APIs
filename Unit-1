
# APIs

[APIs for Beginners - How to use an API](https://www.youtube.com/watch?v=GZvSYJDk-us)

![Plugs plugging into API, showing its multi-functionality](https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fuploads-ssl.webflow.com%2F5b18561112892434c1b06e2a%2F5cd4afac9560dc0ceea6babb_application-programming-interface.jpg&f=1&nofb=1)


## [Defining interface and APIs.](https://www.youtube.com/watch?v=GZvSYJDk-us&t=237s)

**APIs** are:
- made for developers to help them extend their applications with little effort and only a few lines of code.
- API is usually used to refer to web-based APIs
- almost like a contract. It defines how it’s expected to be used and what you can expect to receive from using it. 

Buttons on websites are **interfaces**. They let developers control user interactions while hiding how it *actually* works. e.g. you don't need to know the code that's to convert a colour photo to gray scale? No - you can download a package and an API will convert the image, saving you tons of time.

We have so many web browsers, so how can you write code that will work across all of them? APIs. All web browsers have a set of web APIs they use.

## [Remote APIs](https://www.youtube.com/watch?v=GZvSYJDk-us&t=775s)

Some example of remote APIs:
- Traffic signs on the motorway that are remotely updated
- A drone that is being controlled using your phone
- Shazam uses remote APIs to identify songs
- Using your camera to translate languages instantly
 
 >The data isn't stored on your device, it's sent off to/collected from somewhere else. APIs widens the abilities and power of your phone without needing to be stored locally. 

REST is a very popular standard for APIs. Both terms are sometimes used interchangeably, like Xerox for photocopying. If an API uses the REST style, it's known as a RESTful API.

## [How the web works](https://www.youtube.com/watch?v=GZvSYJDk-us&t=1024s)

```mermaid
graph LR
A(Client)--connects using URL-->B(Server)
B--returns result-->A
```

- **Client** - internet browser
- **URL** (Uniform Resource Locator) - a pathway to a specified location

### HTTP (HyperText Transfer Protocol)

- **Protocol** - similar to API in that it's like a contract. You input something and expect a particular thing to be retrieved. e.g. chant and reply - *when I say hey, you say ho* - it's protocol that *hey* is responded to with *ho* 
- **Transfer** - transferring the request and data from client to server.
- **HyperText** - from HTML. The most important part of web page is the body, which will be HTML. The browser renders the page in your client (the response).

*HTTP verbs* - GET (a standard request like above, only retrieves data), Stateless, POST (used for forms that you submit, e.g. comments)


### Request and response

Query string parameters convey additional info for a request: 
>  everything after the '?' in a search e.g. https://www.reddit.com/r/learnprogramming/search/?q=ask%20reddit&restrict_sr=1&sort=hot&t=hour
>  This reflects within 'Learn Programming' searching for 'Ask Reddit', and restricting the search to hot posts from the past hour.
>  
- **Headers:** communicates even further what's wanted.  Can specify language, if you want a page that's been updated at a certain time (allows for caching) and can embed authentication info so your user stays logged in. 
- **Status codes:** let you know what happened on server's side e.g. missing docs 404 error, content type, how large the data returned is

REST sits on top of these general rules of the internet and also must meet certain constraints to be considered RESTful.

### RESTful API constraints:

Representational State Transfer

1. Uniform interface
2. Client–server
3. Stateless
4. Cacheable
5. Layered system
6. Code on demand (optional)

**How do APIs sit on top of the web technology?**

>
![Client sends request to server using HTTP](https://lh3.googleusercontent.com/pw/ACtC-3cgahbeni5SEbni9_d1kDzKo-UJawChSBkx5YjjGtdiY4ihP-B63C-4PI2nFOMt-Jg2bBEUqQFgAbyPFBJAdtcWbYZRWEBl_zpPxNWXWr2k9kSy9HrB1gJVFWRvjeGL3Ns6SKr6tSH-da7TrPQFrWo=w563-h275-no)
> **2. Client-Server Architecture:** like the web, your program (client) makes a request to the server. You'll probably be using a library to create the request. You make a stateless HTTP request.

> **3. Stateless:** server won't remember anything about particular client. If you want to maintain state you'll have to use  HTTP headers.

- URL (Uniform **Resource** Locator) - a pathway to a specified location: URLs retrieve resources, an identifiable 'thing', almost everything you'd click on is a resource. e.g. on Amazon, all of the listed books are resources. Click on a book, and three is a link to the author, another resource. Click on the author and you'll see a list of their books, another resource. It's pretty much anything, e.g. a link to your user profile, your wishlist


- CRUD: what we want apps to do to our resources. Creating, Reading, Updating and Deleting. 
- APIs work similarly, by:

```mermaid
graph LR
A[Programme] -- GET request --> B((URI))
B --Data, HTTP headers--> A
```

- Body is usually sent in JSON (JavaScript Object Notation) nowadays. Good for structuring and nesting data.,a nd pretty much any language can convert JSON so it is usable.

### HTTP Verbs ii

HTTP verbs are used in APIs:

> | **HTTP Verbs**     | **CRUD**     |
> |-------------|-------------|
> | GET | Read | 
> | POST | Create |
> | PUT | Update |
> | PATCH | Update |
> | DELETE | Delete |

These verbs allow you to interact with any API (as long as they've exposed their REST API). You can remotely automate tasks and mashup APIs. If they're truly restful they should all look pretty similar.
