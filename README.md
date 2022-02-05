<a href="https://twitter.com/sauntimo" target="_blank">
  <svg
    fill="none"
    viewBox="0 0 800 200"
    width="800"
    height="200"
    xmlns="http://www.w3.org/2000/svg"
  >
    <foreignObject width="100%" height="100%">
      <div xmlns="http://www.w3.org/1999/xhtml">
        <style>
          @keyframes rotate {
            0% {
              transform: rotate(5deg);
            }
            100% {
              transform: rotate(-5deg);
            }
          }
          @keyframes fadeIn {
            0% {
              opacity: 0;
            }
            66% {
              opacity: 0;
            }
            100% {
              opacity: 1;
            }
          }
          @keyframes gradientBackground {
            0% {
              background-position: 0% 50%;
            }
            50% {
              background-position: 100% 50%;
            }
            100% {
              background-position: 0% 50%;
            }
          }
          .container {
            font-family: Roboto, system-ui, -apple-system, "Segoe UI", Helvetica,
              Arial, sans-serif, "Apple Color Emoji", "Segoe UI Emoji";
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            margin: 0;
            width: 100%;
            height: 200px;
            background: linear-gradient(-45deg, #fc5c7d, #6a82fb, #05dfd7);
            background-size: 600% 400%;
            animation: gradientBackground 10s ease infinite;
            border-radius: 10px;
            color: white;
            text-align: center;
          }
          h1 {
            font-size: 100px;
            line-height: 1.3;
            letter-spacing: -2px;
            text-shadow: 0 0 10px rgba(0, 0, 0, 0.6);
          }
          .wave {
            display: inline-block;
            visibility: hidden;
            animation: rotate ease-in-out 1s infinite alternate;
          }
          .container:hover .wave {
            visibility: visible;
          }
          .container:hover {
            cursor: pointer;
          }
          .container:hover .name {
            text-decoration: underline;
          }
        </style>
        <div class="container">
          <h1>
            @<span class="name">sauntimo</span>
            <span class="wave">👋</span>
          </h1>
        </div>
      </div>
    </foreignObject>
  </svg>
</a>


# Hi, I'm Tim 👋

### 🔗 Links
[`Github`](https://github.com/sauntimo) [`Stack Overflow`](https://stackoverflow.com/users/4293734/sauntimo) [`LinkedIn`](https://www.linkedin.com/in/sauntimo) [`Twitter`](https://twitter.com/sauntimo) [`Last.fm`](https://last.fm/user/sauntimo) [`Instagram`](https://instagram.com/sauntimo) [`Steam`](https://steamcommunity.com/id/sauntimo)

### 💻 Tech

<div>
  <img src="https://github.com/devicons/devicon/blob/master/icons/typescript/typescript-original.svg" title="Typescript" alt="Nypescript" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/nodejs/nodejs-original.svg" title="Node" alt="Node" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/express/express-original.svg" title="Express" alt="Express" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/postgresql/postgresql-original.svg" title="Postgres" alt="Postgres" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/firebase/firebase-plain.svg" title="Firebase" alt="Firebase" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/googlecloud/googlecloud-original.svg" title="GCP" alt="GCP" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/amazonwebservices/amazonwebservices-original.svg" title="AWS" alt="AWS" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/docker/docker-original.svg" title="Docker" alt="Docker" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/react/react-original.svg" title="React" alt="React" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/nextjs/nextjs-line.svg" title="Next" alt="Next" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/tailwindcss/tailwindcss-plain.svg" title="Tailwind" alt="Tailwind" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/git/git-original.svg" title="Git" alt="Git" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/github/github-original.svg" title="GitHub" alt="GitHub" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/jest/jest-plain.svg" title="Jest" alt="Jest" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/storybook/storybook-original.svg" title="Storybook" alt="Storybook" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/slack/slack-original.svg" title="Slack" alt="Slack" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/vscode/vscode-original.svg" title="VSCode" alt="VSCode" width="40" height="40"/>&nbsp; 
</div>

### 👨‍💻 Experience
I'm a Senior Software Engineer at [`Loopin`](https://letsloopin.com). Here's my [`resumé`](https://github.com/sauntimo/resume).

### 🤝 Open Source

#### [`ts-prune`](https://www.npmjs.com/package/ts-prune)

CLI tool with ~250k+ downloads/month on npm to find unused code in typescript projects. [Added a small feature](https://github.com/nadeesha/ts-prune/pull/140) to allow specfifying a pattern to exclude files from counting toward code use, for instance `.test.ts` - so that functions that were tested but not used anywhere else in the codebase could still be identified and removed.
