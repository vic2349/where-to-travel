# Where to Travel

<p>
  <a href="#中文">中文</a> |
  <a href="#english">English</a>
</p>

<a id="中文"></a>
<details open>
<summary><strong>中文</strong></summary>

## 旅行目的地决策

一个用于帮助 Codex 判断“去哪旅行更适合”的 skill。它会把时间、预算、交通、签证、出发地、舒适度、同行人、兴趣灵感、自然奇观、现场事件和避开项转化为旅行意图标签，再推荐更匹配的目的地。

### 适合什么

- 不知道下一趟旅行去哪。
- 想根据现实条件筛选目的地。
- 想因为食物、酒、动漫、电影、建筑、人物、博物馆或生活方式去旅行。
- 想看极光、日食、鲸鱼、樱花、红叶等不确定性较高的体验。
- 想比较多个目的地哪个更适合。
- 想要一个随机但现实可行的旅行理由。

### 不适合什么

- 详细日程攻略。
- 酒店预订或机票比价。
- 餐厅清单。
- 普通景点介绍。

这些内容只有在服务于“目的地决策”时才会被纳入判断。

### 安装

macOS / Linux:

```bash
git clone https://github.com/vic2349/where-to-travel.git ~/.codex/skills/where-to-travel
```

Windows PowerShell:

```powershell
git clone https://github.com/vic2349/where-to-travel.git "$env:USERPROFILE\.codex\skills\where-to-travel"
```

### 使用示例

```text
使用 $where-to-travel 帮我判断 5 天、不自驾、想看海边电车和动漫氛围，适合去哪。
```

```text
使用 $where-to-travel 随机给我一个旅行盲盒，但我只有 4 天，预算中等，不想太累。
```

### License

MIT License.

</details>

<a id="english"></a>
<details>
<summary><strong>English</strong></summary>

## Travel Destination Decision Skill

A Codex skill for deciding where to travel. It turns constraints, interests, risk tolerance, events, natural phenomena, and avoid-list items into travel intent labels, then recommends destinations that fit the traveler better.

### Good For

- Choosing a next travel destination when you are unsure.
- Filtering destinations by time, budget, transport, visa, departure city, comfort level, and companions.
- Traveling because of food, drinks, anime, films, architecture, people, museums, or lifestyle interests.
- Evaluating uncertain experiences such as aurora, eclipses, whale watching, cherry blossoms, or autumn foliage.
- Comparing multiple destinations.
- Generating a random but realistic travel idea.

### Not For

- Detailed itineraries.
- Hotel booking or flight price comparison.
- Restaurant lists.
- Generic sightseeing introductions.

These topics are only considered when they directly support the destination decision.

### Installation

macOS / Linux:

```bash
git clone https://github.com/vic2349/where-to-travel.git ~/.codex/skills/where-to-travel
```

Windows PowerShell:

```powershell
git clone https://github.com/vic2349/where-to-travel.git "$env:USERPROFILE\.codex\skills\where-to-travel"
```

### Examples

```text
Use $where-to-travel to help me choose a destination for a 5-day trip without driving, with seaside trains and anime-like atmosphere.
```

```text
Use $where-to-travel to generate a random travel idea, but I only have 4 days, a medium budget, and do not want an exhausting trip.
```

### License

MIT License.

</details>
