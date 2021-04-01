## Welcome to GitHub Pages

Go to /list.json for list of jelly bean flavors. Can be used with nightbot like this:
!editcom !flavor $(user) grabbed a $(eval response = `$(urlfetch json https://nategeerdes.github.io/beans/list.json)`; try {json = JSON.parse(response); json[Math.floor(Math.random() * json.length)]} catch(e){`${e}: ${response}`.substr(0, 400)}) jellybean out of the bag!

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
