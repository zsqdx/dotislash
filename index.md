---
title: Dotislash Support
---

# Dotislash

Dotislash runs AI models on your iPhone. Your conversations stay on it unless you turn on the optional web tools or report a response, and once a model is downloaded it works without a connection. It needs iOS 17 or later, and it's rated 18+.

**Contact:** zsqdx2015@gmail.com (Suqin Zhang). We usually reply within two working days.

[Privacy policy](privacy.html) · [Model index](models/)

## Common questions

**Which model should I choose?**
The welcome screen recommends one for your iPhone. On iPhones with 8 GB of memory or more that's Qwen3.5 4B, a 3.15 GB download with the vision file that lets it read photos. iPhones with less memory get a K2 Horizon model, which is text only. The Models tab lists all the models with their sizes, and says so if your iPhone doesn't have the memory for one. Qwen3.8 27B gives better answers than the default but is much slower, and it needs 12 GB of memory. The [model index](models/) lists every model and vision file with its publisher, license, size and the memory it needs, and links to each file on Hugging Face.

**What do Off and On mean at the top of the chat?**
The menu under the chat's title sets how much a model thinks before it answers, and a small brain beside the model's name shows when it's on. With Qwen3.5 4B it's Off or On, and it starts Off. Off answers straight away, and On is for harder questions but takes longer to start. Some models offer Low, Medium and High instead. You can also change it in Settings. If an answer stops while the model is still thinking, raise Longest reply in Settings.

**A download is taking a long time.**
Qwen3.5 4B takes about 5 minutes on 100 Mbit/s Wi-Fi. Downloads continue in the background over Wi-Fi. If a download says "Waiting for Wi-Fi…", join a Wi-Fi network, or cancel it, turn on Settings → Downloads → Use cellular data, and download again. A personal hotspot counts as cellular data. If a download stops, tap Download on the welcome screen, or the arrow beside the model in Models. It continues where it left off when it can, and otherwise it starts over, as it does after you change the cellular setting. Make sure you have enough free storage: the largest model is 7.9 GB with its vision file.

**The app closed while a model was loading or replying.**
iOS closes apps that use more memory than it allows. Dotislash checks before loading a model, but other apps can hold memory too. Close other apps, or restart your iPhone, and try again. A smaller model always uses less memory.

**The app said "Reloading the model…".**
iOS stops an app's use of the GPU when you leave it. If that interrupts a reply, the next message can reload the model first, which takes a moment. Your chat is kept.

**Replies are slow.**
Speed depends on the model and your iPhone. For a quick check, load a model and open Settings → Diagnostics → Measure speed. For comparison, these are measurements with Qwen3.5 4B on an iPhone 18 Pro Max running iOS 27.2, out of its case, over 30 questions. Other iPhones differ.

- With reasoning Off, text starts in about 0.6 seconds and comes at about 33 tokens a second.
- With reasoning On, the answer starts after about 4 seconds.
- A photo's first text comes after about 3 seconds. That's with vision on the GPU, which the app uses only on iPhones with 12 GB of memory.
- The model loads in 0.3 seconds if iOS still has the file cached, and in 1.6 seconds otherwise.

**Why can't I attach a photo?**
Photos need a Qwen model and its vision file, which comes with the model's download. If it's missing, download it from Models → Vision files. You can pick up to four photos at a time.

**Why did the app refuse my message, or replace an answer?**
A filter on your iPhone checks what you type and what the model writes, in English and Chinese. It stops sexual content involving minors, explicit sexual content and instructions that could seriously hurt people, and it answers messages about self-harm with crisis-line information. It doesn't cover hate or graphic violence: the model is told not to write those, and a model can ignore that. The filter works by matching patterns, so it can stop something harmless, and it can miss things. Nothing about this leaves your iPhone. If it got something wrong, tell us.

**Why is Dotislash rated 18+?**
The models are general-purpose, so they can write about adult subjects, and neither the filter nor the rules they're given catch everything. With the web tools on, a model can open any public web page. In Australia, Brazil and Singapore, the App Store confirms that you're an adult before it lets you download an app rated 18+.

**How do I report a harmful or wrong response?**
Tap Report under the response, or touch and hold it and choose Report this response. This opens an email to us with the response, its reasoning and any tool results, shortened if they're long. You see the email before you send it. If Mail isn't available, the app shows our address and the report, ready to copy. Models can make mistakes, so check anything important.

**Can I use my own models?**
No. The App Store version downloads only the models in its catalog, and it doesn't list other files copied into its folder.

**How do I delete my data?**
In Chat, open the list of chats and swipe left on one to delete it. In Models, swipe left on a model to delete it. Deleting the app deletes everything it stored on your iPhone. To have an email you sent us deleted, write to the address above.

## Acknowledgements

Dotislash is built on open-source software, including llama.cpp and Strata's Metal kernels. Their licenses are in Settings → About → Acknowledgements. The models are made by their publishers and come with their own licenses, shown in the Models tab and the [model index](models/).
