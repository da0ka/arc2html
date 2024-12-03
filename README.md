# Arc2HTML
It creates Archives works on web browser. output is compressed, uncompressed and self extracted.
self extracted archives is html format.
## Applications
* `index.html` includes Application list.
* `arc-0.htm`<p>description of code and algorithm
* `arc-sfx-2.htm`<p>modern web browser can open its output
	* solid tiny<p>solid compression, small decoder, slow
	* split tiny<p>split compression, small decoder, slow
	* solid fast<p>solid compression, slightly bigger decoder, fast
	* split fast<p>split compression, slightly bigger decoder, fast
* `arc-sfx2-3.htm`<p>partial browser can't open its output on local system. but its size is slightly smaller and decoding slightly faster than above's
	* mode
		* solid<p>solid compression
		* split<p>split compression. extract all files a time
		* split2<p>split compression. extract one files a time
	* listing<p>create file list
	* LOAD<p>read multiple files
	* Save<p>download all archives
	* kill<p>erase list

others are simple version
