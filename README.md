#  Brendan O'Connor (the JSON Resume)

## How This Works

_data/resume.json has my JSON-formatted resume. It should be pretty self-explanatory; there's a ton of data in there, but the tags go to color on the main website, and "resume: true" determines whether something gets printed on the short resume.

Jekyll takes the JSON and outputs it to the main and resume pages; then a print-only CSS file takes over if someone wants to print either.

No JavaScript is used, anywhere; that isn't necessary, but it was an interesting challenge (particularly for the collapsible sections). 

## Pull Requests

See something you'd change, whether that's a code fix or something you'd like to add to my JSON file? Send a pull request. Or just email me. All code fixes are gratefully appreciated.

## License

(BSD 2-Clause)

Copyright (c) 2015, Brendan O'Connor
All rights reserved.

Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:

1. Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.

2. Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.