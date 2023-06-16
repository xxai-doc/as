<p align="center"><a href="https://xxai.art"><img src="https://cdn.jsdelivr.net/gh/xxai-art/doc/logo.svg"/></a><br/><a href="https://xxai.art"><img src="https://cdn.jsdelivr.net/gh/xxai-art/doc/xxai.svg"/></a></p><p align="center"><a href="https://github.com/xxai-art/doc#readme"><img alt="I18N" src="https://cdn.jsdelivr.net/gh/wactax/img/t.svg"/></a>　<a href="https://groups.google.com/u/0/g/xxai-art"><img alt="Google Groups" src="https://cdn.jsdelivr.net/gh/wactax/img/g-groups.svg"/></a></p>

প্ৰথমে nodejs, [direnv](https://direnv.net) , [bun](https://github.com/oven-sh/bun) সংস্থাপন কৰাটো উপদেশিত, আৰু তাৰ পিছত `direnv allow` পঞ্জিকাত প্ৰৱেশ কৰাৰ পিছত ( [.envrc](https://github.com/xxai-art/doc/blob/main/.envrc) পঞ্জিকাত প্ৰৱেশ কৰাৰ পিছত স্বয়ংক্ৰিয়ভাৱে নিষ্পাদন কৰা হব) ।

অৰ্থ হ’ল: জাপানী, কোৰিয়ান, ইংৰাজীলৈ চীনা অনুবাদ, আন সকলো ভাষালৈ ইংৰাজী অনুবাদ। যদি আপুনি কেৱল চীনা আৰু ইংৰাজী সমৰ্থন কৰিব বিচাৰে, আপুনি কেৱল `zh: en` লিখিব পাৰে।

অৰ্থ হ’ল: জাপানী, কোৰিয়ান, ইংৰাজীলৈ চীনা অনুবাদ, আন সকলো ভাষালৈ ইংৰাজী অনুবাদ। যদি আপুনি কেৱল চীনা আৰু ইংৰাজী সমৰ্থন কৰিব বিচাৰে, আপুনি কেৱল `zh: en` লিখিব পাৰে।

* [ফ্ৰন্ট-এণ্ড ক'ড](https://github.com/xxai-art/web)
* [সামগ্ৰিকভাৱে চাইটটোৰ বাবে ভাষা পেক](https://github.com/xxai-art/web/tree/main/i18n)
* [প্ৰৱেশ মডিউলসমূহৰ বাবে ভাষা পেকসমূহ](https://github.com/wacpkg/user/tree/main/ui.i18n)
* [ৱেবছাইট বহুভাষিক নথিপত্ৰ](https://github.com/xxai-doc)

ফ্ৰন্ট-এণ্ড প্ৰগ্ৰেমিং ভাষা হৈছে [@w5/coffee_plus](http://npmjs.com/@w5/coffee_plus) , যি coffeescript বাক্যবিন্যাসৰ ওপৰত ভিত্তি কৰি কিছুমান বৈশিষ্ট্য যোগ কৰে, চাওক [./coffee_plus.md](./coffee_plus.md) ।

## ৱেবছাইট আৰু নথিপত্ৰৰ আন্তৰ্জাতিককৰণ

তলত দিয়া ৩টা প্ৰকল্পৰ ওপৰত নিৰ্মাণ কৰক

* [@w5/mdt](https://www.npmjs.com/package/@w5/mdt)

  প্ৰত্যয়টো হৈছে `.mdt` , আপুনি বাহ্যিক নথিপত্ৰসমূহ উল্লেখ কৰিবলে `<+ ./coffee_plus/import.js>` ৰ দৰে বাক্যবিন্যাস ব্যৱহাৰ কৰিব পাৰে, আৰু `.md` প্ৰত্যয়ৰ সৈতে মাৰ্কডাউন সৃষ্টি কৰিব পাৰে ।

* [@w5/trmd ৰ দ্বাৰা](https://www.npmjs.com/package/@w5/trmd)

  মাৰ্কডাউন অনুবাদে ক'ড আৰু লিংকসমূহ অনুবাদ নকৰে, আৰু অনুবাদ কৰা বাক্যসমূহ কেশ্ব কৰিব। যদি অনুবাদ পৰিবৰ্তন কৰা হৈছে কিন্তু মূল লিখনী পৰিবৰ্তন কৰা হোৱা নাই, তেন্তে ইয়াক পুনৰ এক্সিকিউট কৰিলে অনুবাদৰ পৰিবৰ্তন অভাৰৰাইট নহ'ব।

* [@w৫/i১৮n](https://www.npmjs.com/package/@w5/i18n)

  `yaml` সৃষ্টি কৰা ৱেবছাইটসমূহ অনুবাদ কৰাৰ বাবে ভাষা ফাইলসমূহ।

### নথিপত্ৰ অনুবাদ স্বয়ংক্ৰিয়কৰণ নিৰ্দেশনা

ক'ড ভঁৰাল [xxai-art/doc](https://github.com/xxai-art/doc) চাওক

প্ৰথমে nodejs, [direnv](https://direnv.net) , [bun](https://github.com/oven-sh/bun) সংস্থাপন কৰাটো উপদেশিত, আৰু তাৰ পিছত `direnv allow` পঞ্জিকাত প্ৰৱেশ কৰাৰ পিছত ( [.envrc](https://github.com/xxai-art/doc/blob/main/.envrc) পঞ্জিকাত প্ৰৱেশ কৰাৰ পিছত স্বয়ংক্ৰিয়ভাৱে নিষ্পাদন কৰা হব) ।

শ শ ভাষালৈ অনুবাদ কৰা বৃহৎ ক’ড বেছটো এৰাই চলিবলৈ মই প্ৰতিটো ভাষাৰ বাবে এটা সুকীয়া ক’ড বেছ তৈয়াৰ কৰিলোঁ আৰু ক’ড বেছটো সংৰক্ষণ কৰিবলৈ এটা সংস্থা সৃষ্টি কৰিলোঁ

পৰিৱেশ চলক `GITHUB_ACCESS_TOKEN` সংহতি কৰিলে আৰু তাৰ পিছত [create.github.coffee](https://github.com/xxai-art/doc/blob/main/create.github.coffee) চলালে স্বয়ংক্ৰিয়ভাৱে ক'ড ভঁৰাল সৃষ্টি হ'ব।

অৱশ্যে, আপুনি ইয়াক ক’ড বেছতো ৰাখিব পাৰে।

অনুবাদ লিপি প্ৰসংগ [run.sh](https://github.com/xxai-art/doc/blob/main/run.sh)

লিপি ক'ডৰ ব্যাখ্যা তলত দিয়া ধৰণে কৰা হয়:

[bunx](https://bun.sh/docs/cli/bunx) npx ৰ এটা প্ৰতিস্থাপন, যি দ্ৰুত। অৱশ্যেই, যদি আপোনাৰ bun সংস্থাপন নাই, আপুনি ইয়াৰ পৰিবৰ্তে `npx` ব্যৱহাৰ কৰিব পাৰে ।

`bunx mdt zh` এ zh পঞ্জিকাত `.mdt` `.md` হিচাপে ৰেণ্ডাৰ কৰে, তলৰ ২টা সংযুক্ত নথিপত্ৰ চাওক

* [কফি_প্লাছ.এমডিটি](https://github.com/xxai-doc/zh/blob/main/coffee_plus.mdt)
* [কফি_প্লাছ.এম.ডি](https://github.com/xxai-doc/zh/blob/main/coffee_plus.md)

`bunx i18n` অনুবাদৰ বাবে মূল ক'ড (যদি আপোনাৰ কেৱল `nodejs` সংস্থাপন কৰা হৈছে, কিন্তু `bun` আৰু `direnv` সংস্থাপন কৰা হোৱা নাই, আপুনি অনুবাদ কৰিবলে `npx i18n` চলাব পাৰে) ।

ই [i18n.yml](https://github.com/xxai-art/doc/blob/main/i18n.yml) বিশ্লেষণ কৰিব, এই দস্তাবেজত `i18n.yml` ৰ বিন্যাস নিম্নলিখিত:

```
en:
zh: ja ko en
```

অৰ্থ হ’ল: জাপানী, কোৰিয়ান, ইংৰাজীলৈ চীনা অনুবাদ, আন সকলো ভাষালৈ ইংৰাজী অনুবাদ। যদি আপুনি কেৱল চীনা আৰু ইংৰাজী সমৰ্থন কৰিব বিচাৰে, আপুনি কেৱল `zh: en` লিখিব পাৰে।

শেষটো হৈছে [gen.README.coffee](https://github.com/xxai-art/doc/blob/main/gen.README.coffee) , যিয়ে প্ৰতিটো ভাষাৰ `README.md` ৰ মূল শিৰোনাম আৰু প্ৰথম উপশিৰোনামাৰ মাজৰ বিষয়বস্তু নিষ্কাশন কৰি এটা প্ৰৱেশ `README.md` সৃষ্টি কৰে। ক'ডটো অতি সহজ, আপুনি নিজেই চাব পাৰে।

বিনামূলীয়া অনুবাদৰ বাবে গুগল এপিআই ব্যৱহাৰ কৰা হয়। যদি আপুনি Google অভিগম কৰিব নোৱাৰে, অনুগ্ৰহ কৰি এটা প্ৰক্সি বিন্যাস আৰু সংহতি কৰক, যেনে:

```
export https_proxy=http://127.0.0.1:7890 http_proxy=http://127.0.0.1:7890 all_proxy=socks5://127.0.0.1:7890
```

অনুবাদ লিপিয়ে `.i18n` পঞ্জিকাত এটা অনুবাদ কৰা কেশ্ব সৃষ্টি কৰিব, অনুগ্ৰহ কৰি ইয়াক `git status` সৈতে পৰীক্ষা কৰক আৰু ইয়াক ক'ড ভঁৰালত যোগ কৰক যাতে পুনৰাবৃত্তিমূলক অনুবাদ এৰাই চলিব পাৰি।

অনুগ্ৰহ কৰি `bunx i18n` চলাওক প্ৰতিবাৰ আপুনি অনুবাদ পৰিবৰ্তন কৰাৰ সময়ত কেশ্ব আপডেইট কৰিবলে ।

যদি মূল লিখনী আৰু অনুবাদ একে সময়তে পৰিবৰ্তন কৰা হয়, কেশ্ব বিভ্ৰান্ত হ'ব, গতিকে যদি আপুনি পৰিবৰ্তন কৰিব বিচাৰে, আপুনি কেৱল এটা পৰিবৰ্তন কৰিব পাৰিব, আৰু তাৰ পিছত কেশ্ব আপডেইট কৰিবলে `bunx i18n` চলাওক।
