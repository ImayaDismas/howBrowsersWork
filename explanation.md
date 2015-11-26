#How Browsers Work

[How Browsers Work][1] has become of interest as people would like to have an understanding on the  [internal browsers' operations][2] so as to help them make better decisions and know the justification behind  [development best practices][3] 

Chrome, Internet Explorer, Firefox, Safari and Opera are the five major browsers used on desktop today. On mobile, the main browsers are Android Browser, iPhone, Opera Mini, UC Browser, the Nokia S40/S60 browsers and Chrome. All of them, except for the Opera browsers, are based on Webkit. The Firefox and Chrome are open source browsers while Safari is partly open source.

[Statistics][6] show that 71% of global desktop browser usage is mainly comprised of Chrome, Firefox and Safari. On mobile, Android Browser, iPhone and Chrome constitute around 54% of usage.

Browser presents the web resources you choose by requesting it from the server and displaying it in the browser window. The resource is usually a HTML document. It may also be a PDF, image or some other type of content. The URI (Uniform Resource Identifier) is used to specify the location of the resource.

The HTML and CSS specifications defines the way the browsers interprets and displays HTML files. The specifications are maintained by a standards organization for the web known as the [W3C (World Wide Consortium)][7].  For compatibility issues for web authors, today most of the browsers more or less conform to these specifications.

Common elements found in almost all browsers' user interfaces They include:

>*1. Home button that takes you to your home page.*

>*2. Back and forward buttons.*

>*3. Bookmarking options.*

>*4. Address bar for inserting a URI.*

>*5. Refresh and stop buttons for refreshing and stopping the loading of the current documents.*

There doesn't exist any formal specification that defines how the user interface of the browser should be developed. It just comes from good practices shaped over years of experience and by browsers copying and imitating each other. The HTML5 specification doesn’t define UI elements a browser must have, but lists some common elements. Among those are the address bar, status bar and tool bar. However, there are features unique to a specific browser like Firefox’s downloads manager.

The main components of the browsers and their functions are:

_1. The user interface:_ UI of a browser is every part of the browser display except the window where you see the requested page. This includes the bookmarking menu, address bar, and back/forward button.

_2. The browser engine:_ Acts as a bridge and marshals actions between the UI and the rendering engine.

_3. The rendering engine:_ It is responsible for displaying requested content. For example if the requested content is HTML, the rendering engine parses HTML and CSS, and displays the parsed content on the screen.
>#####*[Rendering engines:][4]*#####
 * Chrome and Opera: Blink
 * Chrome (iPhone) and Safari: [WebKit][5]
 * Firefox: Gecko
 * Internet Explorer: Trident

_4. Networking:_ For network calls such as HTTP requests, using different implementations for different platform behind a platform-independent interface.

_5. UI backend:_ This is used for drawing basic widgets like combo boxes and windows. This backend exposes a generic interface that is not platform specific. Underneath it uses operating system user interface methods.
JavaScript interpreter: Used to parse and execute JavaScript code.

_6. Data storage:_ This is a persistence layer. The browser may need to save all sorts of data locally, such as cookies. Browsers also support storage mechanisms such as localStorage, IndexDB, WebSQL, and FileSystem.


[1]: http://www.html5rocks.com/en/tutorials/internals/howbrowserswork/
[2]:http://www.html5rocks.com/en/tutorials/internals/howbrowserswork/#The_browser_main_functionality
[3]: https://vimeo.com/44182484
[4]: https://en.wikipedia.org/wiki/Web_browser_engine
[5]: http://www.webkit.org/
[6]: http://gs.statcounter.com/
[7]:http://www.w3.org/
