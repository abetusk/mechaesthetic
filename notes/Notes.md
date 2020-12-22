Notes
===

A place for notes about MechAesthetic.


Sending Email
---

I found `mutt` to be suitable.

To install:

```
sudo apt-get install mutt
```

---

To send formatted HTML (with images hosted elsewhere):

```
mutt -e 'set from="username <user@host>"' -e 'set content_type=text/html' -s 'subject' 'recipient@address'  < file.html
```

---

CSS needs to be embedded in the HTML.
`monolith` is an option, though you'll have to go through and change the images:

```
snap install monolith
monolith 'https://example.com/example-page'
```




