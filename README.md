# Al-Hashemi Infographic Studio

**A bilingual Claude plugin for educators, students, researchers, and media creators.**  
**إضافة كلود لتصميم الإنفوجرافيك الاحترافي والتفاعلي بالعربية والإنجليزية.**

Created for educational and creative use by **Dr. Mahmood Al-Hashemi**.

## Features | المميزات
- Static and interactive infographic planning and production | تصميم إنفوجرافيك ثابت وتفاعلي
- Animated HTML/CSS/JS visual explainers | شرح بصري متحرك
- Arabic RTL and English LTR | دعم العربية والإنجليزية
- 9:16, 16:9, 1:1 layout guidance | مقاسات متنوعة
- No fabricated research statistics or citations | عدم اختلاق بيانات أو مراجع

## Contents
- `.claude-plugin/plugin.json` — plugin metadata
- `.claude-plugin/marketplace.json` — marketplace catalog metadata
- `skills/create-infographic/SKILL.md` — design workflow
- `skills/animate-infographic/SKILL.md` — animation workflow

## Publish to GitHub | النشر
1. Create a **public** GitHub repository named `al-hashemi-infographic-studio`.
2. Upload the **contents of this folder** to the repository root (including the hidden `.claude-plugin` directory). Do not upload only the ZIP.
3. Commit the files to the default branch.
4. Share the repository link with students and colleagues.

## Install | التثبيت
In Claude's plugin interface, look for the option to add a marketplace from GitHub, if available on your account. Enter the GitHub repository reference in the format requested by Claude, then install **al-hashemi-infographic-studio**. Interface labels and availability can change; follow the current official Claude documentation. As an alternative, users with custom plugin upload can try the ZIP package.

**Note:** The plugin provides Claude instructions and workflows. It does not include an MP4 rendering/export service. Animated results may be generated as HTML artifacts and require separate capture/export to video.

## Example prompts | أمثلة

**Arabic:** صمم إنفوجرافيك متحرك 9:16 يشرح خطوات تصوير إعلان قهوة بتقنية Stop Motion، مع نصوص عربية واضحة وحركات سلسة.

**English:** Create a 16:9 interactive infographic comparing three documentary interview lighting setups, with accessible labels and smooth transitions.

## License
MIT. See `LICENSE`.
