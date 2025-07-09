{\rtf1\ansi\ansicpg1251\cocoartf2822
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fswiss\fcharset0 Helvetica;}
{\colortbl;\red255\green255\blue255;}
{\*\expandedcolortbl;;}
\paperw11900\paperh16840\margl1440\margr1440\vieww11520\viewh8400\viewkind0
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural\partightenfactor0

\f0\fs24 \cf0 const apiUrl = 'https://api.jikan.moe/v4/top/anime?limit=30';\
let animeData = [];\
\
async function fetchAnime() \{\
    try \{\
        const response = await fetch(apiUrl);\
        const data = await response.json();\
        animeData = data.data.map(anime => (\{\
            title: anime.title,\
            score: anime.score || 'N/A',\
            members: anime.members,\
            genres: anime.genres.map(g => g.name),\
            synopsis: anime.synopsis || '\uc0\u1053 \u1077 \u1090  \u1086 \u1087 \u1080 \u1089 \u1072 \u1085 \u1080 \u1103 '\
        \}));\
        displayAnime(animeData);\
    \} catch (error) \{\
        console.error('Error:', error);\
    \}\
\}\
\
function displayAnime(animeList) \{\
    const animeListDiv = document.getElementById('animeList');\
    animeListDiv.innerHTML = '';\
    animeList.forEach(anime => \{\
        const div = document.createElement('div');\
        div.className = 'anime-item';\
        div.innerHTML = `<strong>$\{anime.title\}</strong><br>\uc0\u1056 \u1077 \u1081 \u1090 \u1080 \u1085 \u1075 : $\{anime.score\}<br>\u1055 \u1088 \u1086 \u1089 \u1084 \u1086 \u1090 \u1088 \u1099 : $\{anime.members.toLocaleString()\}<br>\u1046 \u1072 \u1085 \u1088 \u1099 : $\{anime.genres.join(', ')\}`;\
        div.onclick = () => showPopup(anime);\
        animeListDiv.appendChild(div);\
    \});\
\}\
\
function showPopup(anime) \{\
    document.getElementById('popupTitle').innerText = anime.title;\
    document.getElementById('popupSynopsis').innerText = anime.synopsis;\
    document.getElementById('popup').style.display = 'flex';\
\}\
\
document.getElementById('closePopup').onclick = () => \{\
    document.getElementById('popup').style.display = 'none';\
\};\
\
document.getElementById('sortButton').onclick = () => \{\
    animeData.sort((a, b) => b.members - a.members);\
    displayAnime(animeData);\
\};\
\
document.getElementById('genreFilter').onchange = (e) => \{\
    const genre = e.target.value;\
    const filteredAnime = genre === 'all' ? animeData : animeData.filter(anime => anime.genres.includes(genre));\
    displayAnime(filteredAnime);\
\};\
\
document.getElementById('refreshButton').onclick = fetchAnime;\
\
fetchAnime();}