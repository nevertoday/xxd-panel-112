<div align="center">

# XXD Panel 112｜سجلّ الورق والخط الذهبي

دع رقعة ورقية غير منتظمة تحمل ذكرى هادئة ولامعة.

[![Codex Skill](https://img.shields.io/badge/Codex-Skill-000000?style=flat-square)](./SKILL.md)

<a href="README.md">简体中文</a> · <a href="README.en.md">English</a> · <a href="README.ja.md">日本語</a> · <a href="README.ko.md">한국어</a> · <strong>العربية</strong>

</div>

## نماذج الأعمال

**نماذج أفقية 16:9 بتقسيم يسار/يمين**

| sample-05 | sample-06 |
|---|---|
| ![sample-05](assets/examples/sample-05.png) | ![sample-06](assets/examples/sample-06.png) |
| ![sample-07](assets/examples/sample-07.png) | ![sample-08](assets/examples/sample-08.png) |

**نماذج عمودية 3:4 بتقسيم أعلى/أسفل**

| sample-09 | sample-10 |
|---|---|
| ![sample-09](assets/examples/sample-09.png) | ![sample-10](assets/examples/sample-10.png) |
| ![sample-11](assets/examples/sample-11.png) | ![sample-12](assets/examples/sample-12.png) |

وُلّدت الأعمال الثمانية بصورة مستقلة من مراجع أصلية مختلفة: الواقع يساراً والتصميم يميناً في الأفقي، والواقع أعلى والتصميم أسفل في العمودي. تستخدم نصاً إنجليزياً ذكياً واجتازت فحص التقسيم الصارم 50:50.

قد تكمن جاذبية الصورة في علاقة أو ملمس أو لحظة صمت، لا في كمية المعلومات. يحافظ هذا Panel على واقع الصورة ويترجم النصف الآخر بلغة بصرية ورقية مستقلة، للملصقات الفنية والنشر والمعارض والمحتوى الاجتماعي والتصميم الخالص.

يعالج انفصال الصورة عن التصميم والزخرفة الزائدة ونقص الفراغ وعدم ثبات التسليم بين النسب.

## الموجّه الأصلي · خمس لغات

[简体中文](references/original-prompt/zh-CN.md) · [English](references/original-prompt/en.md) · [日本語](references/original-prompt/ja.md) · [한국어](references/original-prompt/ko.md) · [العربية](references/original-prompt/ar.md)

## أوضاع الإخراج الأربعة

- `top-bottom`: الصورة الواقعية في الأعلى وتصميم Panel 112 في الأسفل، بنسبة 50% لكل منهما.
- `left-right`: الصورة الواقعية يساراً والتصميم يميناً بنسبة 50% لكل منهما، ولا يُدار إلى تخطيط علوي/سفلي.
- `design-only`: تعرض اللوحة الكاملة ترجمة هذا Panel فقط، والصورة مرجع لا يظهر.
- `wallpaper-pack`: أنشئ لوحة كاملة مستقلة لكل جهاز.

## البدء

```bash
git clone https://github.com/nevertoday/xxd-panel-112.git
mkdir -p ~/.codex/skills
ln -s "$(pwd)/xxd-panel-112" ~/.codex/skills/xxd-panel-112
```

يمكنك أيضاً تثبيته مباشرةً باستخدام `npx skills`:

```bash
npx skills add https://github.com/nevertoday/xxd-panel-112 --skill xxd-panel-112
```

يجلب الأمر المستودع من GitHub ويثبّت الـ Skill ذي الاسم نفسه. وللتثبيت العام في Codex أضف `--global --agent codex --yes`.

بعد التثبيت أعد تشغيل جلسة الوكيل ثم استدعِ `$xxd-panel-112`.

## الترخيص

يُقدَّم المشروع بموجب **PolyForm Noncommercial License 1.0.0**. النص الكامل في [LICENSE](LICENSE) والصفحة الرسمية <https://polyformproject.org/licenses/noncommercial/1.0.0>.

- يُسمح بالاستخدام الشخصي والتعليمي والبحثي والتجريبي والهوايات والاستخدام العام المؤهل.
- للأغراض غير التجارية يمكن الاستخدام والنسخ والتعديل وإنشاء المشتقات والتوزيع مع إرفاق الترخيص والإشعارات المطلوبة.
- تتطلب المنتجات والخدمات التجارية والتسليم بمقابل وبيع الوصول أو الاستخدام التجاري المتوقع إذناً كتابياً منفصلاً.
