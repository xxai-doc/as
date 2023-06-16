<p align="center"><a href="https://xxai.art"><img src="https://cdn.jsdelivr.net/gh/xxai-art/doc/logo.svg"/></a><br/><a href="https://xxai.art"><img src="https://cdn.jsdelivr.net/gh/xxai-art/doc/xxai.svg"/></a></p><p align="center"><a href="https://github.com/xxai-art/doc#readme"><img alt="I18N" src="https://cdn.jsdelivr.net/gh/wactax/img/t.svg"/></a>　<a href="https://groups.google.com/u/0/g/xxai-art"><img alt="Google Groups" src="https://cdn.jsdelivr.net/gh/wactax/img/g-groups.svg"/></a></p>

# xxAI.art

ৱেবছাইট ক'ডৰ এটা অংশ মুক্ত উৎস, অনুবাদক অনুকূল কৰাত সহায় কৰিবলৈ আদৰণি জনোৱা হৈছে।

## ফ্ৰন্ট-এণ্ড ক'ড

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
