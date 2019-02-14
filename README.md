### [Markdown Service Tools](http://brettterpstra.com/projects/markdown-service-tools/)

This is the latest version of Markdown Service Tools at the time of this commit. The only modifications made were adding `Get Text` to the workflow for Markdown To RTF when it didn't work for me to test in automator what the erorr was.

Works great as is just needed to have
`/usr/local/bin/multimarkdown` available which I did by creating a symlink from my macport installations of multimarkdown.

```bash
sudo port install multimarkdown
cd /usr/local/bin/
ln -s /opt/local/bin/multimarkdown multimarkdown
```

#### References

* [ Markdown Service Tools: in-place Markdown to RTF](http://brettterpstra.com/2013/03/08/new-in-the-markdown-service-tools-in-place-markdown-to-rtf/)

### Credits

[Brett](http://brettterpstra.com/contact/) Is repsonsible for all of this code I simply put it in github so I can save my changes. Was unable to find the project in github or I would have just forked it.
