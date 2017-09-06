# pwdmasher
Password Masher - Make unique complex passwords per domain from simple local passwords - open javascript


pwdmasher.html - (public version - modify to make private)

Password Masher generates secure passwords by mashing together
domain name and a normal simple password to create domain-unique,
strong passwords. For instance password12 might be converted to 
3L*rTufI=pXA2lMnVB6lNsWAxGhLp~bK

This means no website or domain ever has the same password on file, and
easy to remember, simple passwords can be used locally on pwdmasher without 
those passwords being exposed externally.


** Security in use **

For security, this should be downloaded and then run as a local file via 
your browser (eg file:///home/pwdmasher.html ). Bookmark it for ease 
of access.

This file makes NO CONNECTION to the internet. You can confirm this with
network viewer under Web Development tools on your browser.

All code is open (no external or obfuscated files) and can be 
inspected below. Verify there is no outbound internet element
and double check with Network Inspector that no outbound connections
are made.
   
   
** Personalisation **

The code here should be personalised for additional security

- dateofbirth, schoolname, MD5seed1, MD5seed2 can be modified freely
	(they act as seeds to the hashing function)

- for coders, additional 'blendtype' strings can be added into blendit 
    function and selected with the blendtype variable
    
- the hash and blend method can be used in other programming languages
	or applications to produce identify output. We like the
	openness of Javascript on an HTML page because it is easily 
	inspected and verified
	
- for developers you could extend this to add a hash to the login URL
	and then mash this too, to provide a unique password per visit
    
** Validation **

With original settings, output from domain:bbc.com and password:1234
is zi+vf5p!tb0E7M?XByjQq?vAdHhO@s#Z

If you do personalise the code, remember to keep a backup copy and 
a test output.

Copyright 2017 Saul Dobney (www.notanant.com)

This program is free software; you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation; either version 2 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program; if not, write to the Free Software
Foundation, Inc., 51 Franklin Street, Fifth Floor, Boston,
MA 02110-1301, USA.



