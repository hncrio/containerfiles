# containerfiles
Containerized applications for local usage

Influenced by [jessfrazz/dockerfiles](https://github.com/jessfraz/dockerfiles) \
The main difference is that I use fedora-minimal instead of debian-slim \

**Q:** Why don't you use toolbox, or flatpak in silverblue ?
**A:** Well I want my configuration files and images in monorepo tracked by git,and for now I don't know how to do that with native tools.

**Q:** What is your motivation behind this? 
**A:** Modularity and granularity is great. Having an immutable OS decouples the underlying os with the daily workloads. Having said that it requires more time to maintain and implement new apps. But there is no dependency conflicts, you are free to have multiple versions of a single app. Migration is easier than ever. 

**Q:** Why fedora? 
**A:** Fedora is behind the most important upstream projects. I find fedora is more consise in terms of engineering.  



