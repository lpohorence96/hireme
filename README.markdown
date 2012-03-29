### hireme

So, you want a job in bleeding-edge machine-to-machine technologies?  Let's see if you have what it takes to ride with the cloud console-cowboys.

1. Read up on us: [2lemetry.com](http://2lemetry.com), [cassandra.io](http://cassandra.io). *Sidenote*: You should probably know what Skynet is.

1. **fork** this repository. Show us you have *git* skillzez.

1. `cd` into the `resumes` folder (or create it), add a resume in the format of your choice. MS Word docs will be **ignored**.

1. Submit a *pull* request with your changes. 

1. We're not _always_ near a computer, so use our API to notify us you're interested. Make a `POST` request using any language/client of your choice to the endpoint below. The body of the request should be `JSON`:

```
{
  github_username: "<github_username>"
}


http://api.m2m.io/1/hireme
```