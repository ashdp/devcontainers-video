# Purpose
Practice https://www.youtube.com/watch?v=SDa3v4Quj7Y My Favorite Way To Handle Dev Environments | VS Code Devcontainers

# Summary
1. Install Git Desktop, VS Code, Docker Desktop, WSL
2. VS Code Extension: Remote Development
3. Create simple Github repo for the files (readme and gitignore enough)
4. Ctrl+Shift+P --> devcontainers: Git clone into container --> Add URL from previous step
5. Choose: Linux Universal Container --> No additional tools needed

# Bit More
6. I had to install my git creds as per https://github.com/ashdp/github-by-examples
7. mkdir simple-nextjs-app ; cd simple-nextjs-app ; npx create-next-app@latest . ; npm run dev

# Rest of Video
8. Talks about customising the default Linux Universal devContainer (e.g. if it was missing ffmpeg we can create a Dockerfile, add apt install -y ffmpeg and rebuild/restart the running container)
9. By comitting the Dockerfile in the previous step to Github, then you can open in 'Github Codespaces' the entire environment in a web browser and code there!

# John Savill Explains DevContainers and Codespaces https://youtu.be/-D2BwSV9Pg0?si=epCO6UvLsMd4rWxb
10. Good video coming more from the perspective of someone else's repo with a DevContainer setup.
