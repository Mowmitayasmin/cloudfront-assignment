# cloudfront-assignment

## Deployment Explanation

I created a simple static website using HTML, CSS, and JavaScript, and stored it in a GitHub repository called `cloudfront-assignment`.

To deploy the site, I used **GitHub Pages**:

- I went to the **Settings > Pages** section in my repository.
- I selected the **main branch** and set the root (`/`) folder as the source.
- GitHub automatically deployed the site and provided a live URL:  
    https://mowmitayasmin.github.io/cloudfront-assignment/

GitHub Pages also enforces **HTTPS**, which means the site is delivered securely.

The deployment process is simple and free, making it a great choice for hosting static sites.

## Explanation of CDNs

A **Content Delivery Network (CDN)** is a globally distributed network of servers that deliver content to users based on their geographic location.

### Why We Use a CDN:
- A CDN like **CloudFront** stores **cached copies** of your content on **edge servers** around the world.
- It delivers content from the **closest server**, improving **speed**, **performance**, and **load times**.
- CDNs can handle **large traffic volumes** efficiently and improve **site availability** and **security**.

### Tradeoffs of Using CDNs:
- Can be **slightly more complex** to configure in certain cases.
- **Cache invalidation** (updating changed files across servers) can introduce minor delays.
- For **high-traffic sites**, using a CDN can **increase costs**.