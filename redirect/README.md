# URL Redirect

To recreate the redirect:

```bash
aws s3 cp awscr s3://s3redirect/awscr --acl public-read --website-redirect https://www.youtube.com/channel/UCh8IUv9B3liJUuQhGo0c9sA
```
