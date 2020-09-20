# video & audio in HTML 
HTML5 comes with elements for embedding rich media in documents — \<video> and \<audio> — which in turn come with their own APIs for controlling playback, seeking, etc. This article shows you how to do common tasks such as creating custom playback controls.
## Definition and Usage
The \<video> tag is used to embed video content in a document, such as a movie clip or other video streams.

The \<video> tag contains one or more \<source> tags with different video sources. The browser will choose the first source it supports.

The text between the \<video> and \</video> tags will only be displayed in browsers that do not support the \<video> element.

There are three supported video formats in HTML: MP4, WebM, and OGG.

Example
Play a video:

\<video width="320" height="240" controls>
  \<source src="movie.mp4" type="video/mp4">
  \<source src="movie.ogg" type="video/ogg">
  Your browser does not support the video tag.
\</video>
