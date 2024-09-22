# Hi there 👋, Mohammed Sarwar Khan

🔭 I’m currently working on Zenith Notes  
🌱 I’m currently learning JavaScript  
👯 I’m looking to collaborate on Zenith Notes and on future projects  
📫 Reach me: mohd.sarwar.code@gmail.com  

---

### About Me
- 💻 Web Developer with a passion for problem-solving.
- 🌐 Exploring the potential of Web3 and Blockchain in the tech space.
- 🚀 Currently building Zenith Notes, a next-gen platform for students.

---

### Languages, Tools, and Technologies:
<p align="left">
  <img src="https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black" />
  <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  <img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white" />
  <img src="https://img.shields.io/badge/Web3-F16822?style=for-the-badge&logo=web3dotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/Blockchain-121D33?style=for-the-badge&logo=blockchain&logoColor=white" />
</p>

---

### GitHub Stats:

<table align="center" style="table-layout:fixed; width: 100%; padding: 10px;">
  <tr>
    <td align="center" style="padding: 10px; width: 33%;">
      <img src="https://github-readme-stats.vercel.app/api?username=mohfazam&show_icons=true&theme=tokyonight" alt="Mohfazam's GitHub stats" width="350" />
    </td>
    <td align="center" style="padding: 10px; width: 33%;">
      <img src="https://github-readme-streak-stats.herokuapp.com/?user=mohfazam&theme=tokyonight" alt="Mohfazam's GitHub Streak" width="350" />
    </td>
    <td align="center" style="padding: 10px; width: 33%;">
      <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=mohfazam&layout=compact&theme=tokyonight" alt="Top Languages" width="350" />
    </td>
  </tr>
</table>

---

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif"><h3 align="center">Statistics</h3>
<div align="center">
<a href="https://github.com/mohfazam>
<img align="center" src="http://github-profile-summary-cards.vercel.app/api/cards/stats?username=mohfazamtheme=2077" height="180em" />
<img align="center" src="http://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=mohfazam&theme=2077" height="180em" style="margin = 1rem" />
<img align="center" src="http://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=mohfazam&theme=2077" height="180em " style="margin = 1rem"/>
<img align="center" src="http://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=mohfazam&theme=2077" height="180em" style="margin = 1rem"/>
<img align="center" src="http://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=mohfazam&theme=2077" height="180em" style="margin = 1rem" />
</div>
---


import React from 'react';

const GitHubStats = ({ username, theme = '2077' }) => {
  const cards = [
    {
      src: `http://github-profile-summary-cards.vercel.app/api/cards/stats?username=${username}&theme=${theme}`,
      alt: "GitHub Stats"
    },
    {
      src: `http://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=${username}&theme=${theme}`,
      alt: "Most Commit Language"
    },
    {
      src: `http://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=${username}&theme=${theme}`,
      alt: "Repos per Language"
    },
    {
      src: `http://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=${username}&theme=${theme}`,
      alt: "Productive Time"
    },
    {
      src: `http://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=${username}&theme=${theme}`,
      alt: "Profile Details"
    }
  ];

  return (
    <div className="flex flex-col items-center w-full max-w-5xl mx-auto p-4">
      <img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" alt="Separator" className="w-full mb-4" />
      <h3 className="text-2xl font-bold mb-6">Statistics</h3>
      <div className="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
        {cards.map((card, index) => (
          <div key={index} className={`bg-gray-800 rounded-lg shadow-lg overflow-hidden ${index === 4 ? 'col-span-full' : ''}`}>
            <img src={card.src} alt={card.alt} className="w-full h-auto" />
          </div>
        ))}
      </div>
    </div>
  );
};

export default GitHubStats;



### Future Plans:
- 🚀 Exploring AI integrations with Web3 and Blockchain.
- 💡 Working on decentralized apps (DApps) as side projects.

---

### Featured Projects:
- [Zenith Notes](https://github.com/yourrepo/zenith-notes): A notes-sharing platform for college students with year-wise resources, question banks, and assignments.
- [Web Based Crypto Wallet](https://github.com/Mohfazam/Crypto-Wallet): A web-based crypto wallet with key-pair generation and transaction interface, laying the groundwork for blockchain integration.
- [Tic-Tac-Toe](https://github.com/yourrepo/tic-tac-toe): A JavaScript-based Tic-Tac-Toe game with win pattern checks and game reset functionality.

---

### Certifications:
- JavaScript Algorithms and Data Structures Certification (freeCodeCamp)
- Git and GitHub for Beginners (Coursera)

---

### Programming Profiles:
- [LeetCode](https://leetcode.com/Mohfazam): 100+ problems solved.
- [GeeksforGeeks](https://auth.geeksforgeeks.org/user/Mohfazam/profile): Consistent problem-solving with various algorithms.
- [CodeForces](https://codeforces.com/profile/mohfazam): 850+ rating on CodeForces.

---

### Tech Stack:
- **Frontend**: HTML5, CSS3, JavaScript (React)
- **Backend**: Node.js (for future projects), Web3.js (for DApp development)
- **Version Control**: Git, GitHub
- **Database**: MongoDB, exploring decentralized storage
- **Hosting**: Vercel (for deploying projects)

---

### Contribution Graph:
<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=mohfazam&theme=tokyo-night" alt="Contribution Graph" />
</p>

---

### GitHub Trophies:
<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=mohfazam&theme=algolia&no-bg=true&row=1&column=3" alt="GitHub Trophies" />
</p>

---

### Visitors:
![Visitors](https://komarev.com/ghpvc/?username=mohfazam&label=PROFILE+VIEWS&style=flat-square&color=blue)
