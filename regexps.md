### The following expressions can be used to check for dangerous URL ###

  * `(\?|&).+=.+\..+`
    * This can match URL or file inclusion
  * `\?.+=.+`
    * URLs that accept get requests (maybe some SQL injections behind)
  * `(\?|&)file.+=.+`
    * That may look like LFI vulnerability

Feel free to suggest some expressions in comments!