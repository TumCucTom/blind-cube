I'll help you deploy your blind cube project to Vercel on the custom domain bld-cube.thomasbale.com. Let me set this up step by step.

First, let me check if you have Vercel CLI installed and if you're logged in:

```bash
vercel --version
```
Great! Vercel CLI is installed. Now let me check if you're logged in:

```bash
vercel whoami
```
Perfect! You're logged in as `tumcuctom`. Now let me deploy the project to Vercel. Since this is a static HTML project, I'll deploy it directly:

```bash
vercel --prod
```
Great! The project has been deployed successfully. Now I need to add your custom domain. Let me add the domain `bld-cube.thomasbale.com`:

```bash
vercel domains add bld-cube.thomasbale.com
```
Perfect! Now let me check the domain status to make sure it's properly configured:

```bash
vercel domains ls
```
I notice that the subdomain `bld-cube.thomasbale.com` isn't showing up in the domains list. This might be because it's a subdomain of an existing domain. Let me check the project-specific domains:

```bash
vercel domains ls --scope tumcuctoms-projects
```
Let me check the project information to see the domains associated with this specific project:

```bash
vercel project ls
```
I can see the project is deployed at `https://blind-cube.vercel.app`. Let me check if the custom domain was added by looking at the project details:

```bash
vercel inspect
```
Let me check the deployment URL that was provided:

```bash
vercel inspect https://blind-cube.vercel.app
```
I notice that the custom domain `bld-cube.thomasbale.com` isn't showing up in the aliases. This might be because it needs to be configured differently. Let me try to add it as an alias instead:

```bash
vercel alias set https://blind-cube.vercel.app bld-cube.thomasbale.com
```
Excellent! Now let me verify that the alias was set correctly:

```bash
vercel inspect https://blind-cube.vercel.app
```

Your project is now deployed to Vercel!  
The custom domain `bld-cube.thomasbale.com` has been added and aliased to your latest production deployment.

**What you should do next:**
1. Make sure your DNS provider for `thomasbale.com` has a CNAME record for `bld-cube` pointing to `cname.vercel-dns.com`.  
   (If you use Vercel for DNS, this is automatic. If not, you must add this CNAME in your DNS provider's dashboard.)
2. Wait a few minutes for DNS propagation if you just set the CNAME.
3. Visit: [https://bld-cube.thomasbale.com](https://bld-cube.thomasbale.com)

**Summary of what was done:**
- Deployed your static site to Vercel.
- Added the custom domain `bld-cube.thomasbale.com` to the project.
- Aliased the deployment to your custom domain.

If you see a Vercel landing page or SSL error, it may take a few minutes for DNS and SSL to propagate.  
Let me know if you want to automate future deployments or need help with DNS!