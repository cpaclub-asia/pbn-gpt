# PBN (Private Blog Network) Project - GPT Content

## 🌐 Overview

Задача - генерация конента на основе GPT


<details>
<summary>🤝 Agreements</summary>
   
1. Считаем, что у нас есть домени и сайт с контентом
</details>



## 📋 Workflow
1. Сгенерировать: title, description
2.1. Сгенерировать структуру сайта
2.2. теги (тематика о чем рассказываем)
2.3. ключевые слова (ключ, что ищет аудитория)
2.4. боли аудитории(как им можем помочь)/портрет аудитории
3. Генерация названий статей+снипета на GPT4 / Своя сетка на датасете Google, чтобы было интересно, релевантно
4. Генерация структуры статьи на GPT4. Позже GPT3, для экономии и общего кругозора. Смысла с своей сетке наверное нет, а может есть
5. Генерация контента статей на GPT4, позже на своей сетке, чтобы было уникально и не заметно. Плюс лучший опыт на основе выдачи гугла. (из снипетов своих в пункте 3)

📝 Make a list from:
- Google SERP (our/competitors keywords)
- Outgoing links from big sites (Wikipedia, GitHub, GitLab, ...), also can take Top-3 from Google
- Majestic Million

using Semrush or wget+rapser

#### 📝 Drop Domains
look for Domains, that are Expired(Potential New Drops) or Free/Available (old drops)


#### Potential New Drops and Bids technology
📝 To-do



### ✏️ Content
🔍 Parsed from web.archive.org or commoncrawl.org
⚙️ Processing of parsef content:
- Use our own tools to parse content
- Restore content as CSV for later upload to our WordPress


⚙️ Process for drop domains:
1. Make a list of potential domains
2. Check the list by combining domain and parsed content





### ⚙️ Domain Selection
- Check the list of drop domains
- Consider factors such as content, PR (Page Rank), and manual domain selection

### ⬆️ WordPress Integration
After buying a domain, upload the old information to WordPress.

📊 **Project Workflow**




   - Perform manual domain selection based on factors like content quality, PR, etc.

   - csv / After domain acquisition, upload the old information to WordPress





## ✨ **Scripts and Folders**

**./content**

This folder contains scripts related to content parsing and restoration.

read [content/README.md](content/README.md) for more details

**./domains**

This folder contains scripts related to domain management.

read [domains/README.md](content/README.md) for more details
