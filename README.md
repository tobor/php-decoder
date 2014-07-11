The PHP Decoder
===================
PHP decoder is an half-automated tool that de-obfuscates encoded/encrypted PHP scripts.

Usage
===================
A set of decoded files is generated upon execution. Files are named in the form of eval.X.php, where X is an increasing number starting from "1".

<pre>
%> ./sapi/cli/php encoded.php
</pre>

One of the result files will be the clear text. Enjoy ;-P (Well, garbage text expected)


