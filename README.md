# Web 3 Blog

This is a censorship resistant blog template that is configured to be published to Swarm whenever there is a change in the main branch of the repository.

A minimum amount of knowledge is required from you to maintain such a blog. Below is information on how to start your own blog step by step.

1. Fork this repository.

2. Create your private key

3. Add it to the repository settings. Whoever owns the private key owns the blog. Don't share it with anyone.

4. Open `content/posts/my-first-post.md` file and edit it. To add a new post, create a new file with a similar structure. Save it.

5. Open Actions tab, open completed worflow and find `Site URL`. Every time you make changes, the blog will be available at this link. This link can be shared with other people. 

The blog could be accessible by the local url `http://<YOUR_CID>.swarm.localhost:1633/`. Every person who has Desktop installed can access your blog.

To make your blog available on a beautiful name, create an ens domain and add Feed Manifest to it.
