The PHP Decoder
===================
PHP decoder is an half-automated tool that de-obfuscates encoded/encrypted PHP scripts.

Usage
===================
Upon execution a set of deocded files is generated, named as eval.X.php. X is an increasing number starting from "1".

<pre>
%> ./sapi/cli/php encoded.php
</pre>

One of the result files will be the clear text. Enjoy ;-P (Well, garbage text expected)


