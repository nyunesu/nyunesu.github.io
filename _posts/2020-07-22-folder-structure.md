---
title: "Utility script to organize Unity's folders"
date: 2020-07-22
categories:
  - blog
tags:
  - development
---



Hello!

Another quick thing that I thought it'd be great to share. I made a tiny script to generate a simple folder structure in Unity, so you can save a few minutes you'd spend organizing your folders.

<blockquote class="twitter-tweet"><p lang="en" dir="ltr">I made a simple script to generate a folder structure in <a href="https://twitter.com/unity3d?ref_src=twsrc%5Etfw">@unity3d</a> so I don&#39;t have to organize each new project<br><br>Feel free to use/distribute/customize, whatever you want<a href="https://t.co/tM13BJNwbS">https://t.co/tM13BJNwbS</a><a href="https://twitter.com/hashtag/gamedev?src=hash&amp;ref_src=twsrc%5Etfw">#gamedev</a> <a href="https://twitter.com/hashtag/madewithunity?src=hash&amp;ref_src=twsrc%5Etfw">#madewithunity</a> <a href="https://t.co/evrRKcF7fY">pic.twitter.com/evrRKcF7fY</a></p>&mdash; nyunesu (@nyunesu) <a href="https://twitter.com/nyunesu/status/1285733937952718850?ref_src=twsrc%5Etfw">July 22, 2020</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

As I said on the tweet, feel free to use/customize/distribute or whatever you want to.

```csharp
using System.IO;
using UnityEditor;
using UnityEngine;

namespace Tools
{
    public static class GenerateFolderStructure
    {
        [MenuItem("Tools/Nyunesu/Generate Folder Structure")]
        public static void Execute()
        {
            Directory.CreateDirectory(Application.dataPath + "/[Debug]");
            Directory.CreateDirectory(Application.dataPath + "/Art");
            Directory.CreateDirectory(Application.dataPath + "/Art/Animations");
            Directory.CreateDirectory(Application.dataPath + "/Art/Materials");
            Directory.CreateDirectory(Application.dataPath + "/Art/Models");
            Directory.CreateDirectory(Application.dataPath + "/Art/Textures");
            Directory.CreateDirectory(Application.dataPath + "/Audio");
            Directory.CreateDirectory(Application.dataPath + "/Audio/Music");
            Directory.CreateDirectory(Application.dataPath + "/Audio/Sound");
            Directory.CreateDirectory(Application.dataPath + "/Code");
            Directory.CreateDirectory(Application.dataPath + "/Code/Scripts");
            Directory.CreateDirectory(Application.dataPath + "/Code/Scripts/Environment");
            Directory.CreateDirectory(Application.dataPath + "/Code/Scripts/Framework");
            Directory.CreateDirectory(Application.dataPath + "/Code/Scripts/Tools");
            Directory.CreateDirectory(Application.dataPath + "/Code/Scripts/UI");
            Directory.CreateDirectory(Application.dataPath + "/Code/Shaders");
            Directory.CreateDirectory(Application.dataPath + "/Docs");
            Directory.CreateDirectory(Application.dataPath + "/Editor");
            Directory.CreateDirectory(Application.dataPath + "/Level");
            Directory.CreateDirectory(Application.dataPath + "/Level/Physics");
            Directory.CreateDirectory(Application.dataPath + "/Level/Prefabs");
            Directory.CreateDirectory(Application.dataPath + "/Level/Scenes");
            Directory.CreateDirectory(Application.dataPath + "/Level/UI");
            Directory.CreateDirectory(Application.dataPath + "/Plugins");
            Directory.CreateDirectory(Application.dataPath + "/Resources");
            Directory.CreateDirectory(Application.dataPath + "/StreamingAssets");
            Directory.CreateDirectory(Application.dataPath + "/ThirdParty");
            Directory.CreateDirectory(Application.dataPath + "/WebGLTemplates");
        }
    }
}
```



That's it, I hope that's helpful for you somehow!

See ya! (:



------



Subscribe to my mailing list so you don't miss any post or game I publish.

[http://nyune.su/newsletter](http://nyune.su/newsletter)