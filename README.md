# Arc2HTML
It creates Archives works on web browser. output is compressed, uncompressed and self extracted.
self extracted archives is html format.
## Applications
* `index.html` includes Application list.
* `arc-0.htm`<p>description of code and algorithm
* `arc-sfx-2.htm`[demo](https://codepen.io/xezz/pen/yyBNVKJ)<p>modern web browser can open its output
	* solid tiny<p>solid compression, small decoder, decoding is slow
	* split tiny<p>split compression, small decoder, decoding is slow
	* solid fast<p>solid compression, slightly bigger decoder, decoding is fast
	* split fast<p>split compression, slightly bigger decoder, decoding is fast
* `arc-sfx2-3.htm`[demo](https://codepen.io/xezz/pen/emOmKpz)<p>partial browser can't open its output on local system. but its size is slightly smaller and decoding slightly faster than above's
	* html
		* raw<p>output raw decoder
		* tiny<p>output compressed decoder
		* clear<p>remove compressed string after load contents
	* mode
		* solid<p>solid compression
		* split<p>split compression. extract all files before download
		* split2<p>split compression. extract one files a time
	* listing<p>create file list
	* LOAD<p>read multiple files
	* Save<p>download all archives
	* kill<p>erase list

others are simple version
