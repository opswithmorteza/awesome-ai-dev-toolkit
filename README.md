# AI Development Toolkit | راهنمای ابزارهای توسعه با هوش مصنوعی

فهرست عمومی و دسته‌بندی‌شده برای انتخاب ابزارهای کدنویسی، طراحی سایت، UI/UX، اتصال GitHub و کاهش مصرف توکن.

این مخزن راهنمای انتخاب ابزارهاست. هر ۳۳ پروژهٔ فهرست‌شده به‌صورت عمومی در حساب opswithmorteza فورک شده‌اند؛ در هر دسته لینک فورک و مخزن اصلی کنار هم آمده است. برای نصب، مجوز استفاده و آخرین سازگاری، مستندات مخزن اصلی هر ابزار را ببینید.

## اگر از Codex استفاده می‌کنید

| ابزار | چه زمانی استفاده کنیم؟ | نحوه استفاده |
|---|---|---|
| [GitHub MCP — فورک](https://github.com/opswithmorteza/github-mcp-server) · [اصلی](https://github.com/github/github-mcp-server) | کار با مخزن، ایشو و Pull Request | اتصال سرور MCP و اعطای دسترسی لازم به حساب مقصد |
| [Context7 — فورک](https://github.com/opswithmorteza/context7) · [اصلی](https://github.com/upstash/context7) | دریافت مستندات کتابخانه‌ها | اتصال MCP و درخواست مستندات مربوط به نسخه مورد استفاده |
| [Playwright MCP — فورک](https://github.com/opswithmorteza/playwright-mcp) · [اصلی](https://github.com/microsoft/playwright-mcp) | بررسی رفتار سایت در مرورگر | اتصال MCP؛ سپس درخواست بررسی صفحات و جریان کاربری |
| [Serena — فورک](https://github.com/opswithmorteza/serena) · [اصلی](https://github.com/oraios/serena) | جست‌وجو و ویرایش دقیق در پروژه‌های بزرگ | اتصال MCP و معرفی پروژه؛ بازیابی نمادها و ارجاع‌های مرتبط |
| [RTK — فورک](https://github.com/opswithmorteza/rtk) · [اصلی](https://github.com/rtk-ai/rtk) | کوتاه‌کردن خروجی فرمان‌های توسعه | ابزار خط فرمان؛ راهنمای اختصاصی Codex در مخزن اصلی |
| [UI UX Pro Max — فورک](https://github.com/opswithmorteza/ui-ux-pro-max-skill) · [اصلی](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill) | انتخاب سبک، رنگ، تایپوگرافی و الگوهای رابط | نصب نسخه مهارت مخصوص Codex طبق راهنمای پروژه |

پیشنهاد شروع: اتصال GitHub، مستندات Context7 و بررسی مرورگر؛ برای پروژه‌های بزرگ Serena و برای خروجی طولانی فرمان‌ها RTK را ارزیابی کنید. نصب همه ابزارها به‌صورت هم‌زمان ضروری نیست.

## اگر از Claude Code استفاده می‌کنید

| ابزار | کاربرد | نحوه استفاده |
|---|---|---|
| [GitHub MCP — فورک](https://github.com/opswithmorteza/github-mcp-server) · [اصلی](https://github.com/github/github-mcp-server) | مدیریت کارهای GitHub | ثبت سرور در تنظیمات MCP کلاینت |
| [Context7 — فورک](https://github.com/opswithmorteza/context7) · [اصلی](https://github.com/upstash/context7) | مستندات به‌روز هنگام کدنویسی | اتصال MCP و درخواست مستندات مرتبط |
| [Playwright MCP — فورک](https://github.com/opswithmorteza/playwright-mcp) · [اصلی](https://github.com/microsoft/playwright-mcp) | کار با مرورگر و بررسی سایت | اتصال MCP و تعریف سناریوی بررسی |
| [Serena — فورک](https://github.com/opswithmorteza/serena) · [اصلی](https://github.com/oraios/serena) | تحلیل ساختار و ارجاع‌های کد | اتصال MCP و فعال‌کردن پروژه |
| [RTK — فورک](https://github.com/opswithmorteza/rtk) · [اصلی](https://github.com/rtk-ai/rtk) | کاهش خروجی اضافی فرمان‌ها | راه‌اندازی یکپارچه‌سازی Claude Code طبق README اصلی |
| [UI UX Pro Max — فورک](https://github.com/opswithmorteza/ui-ux-pro-max-skill) · [اصلی](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill) | راهنمای طراحی UI/UX | نصب نسخه سازگار با Claude Code طبق مستندات اصلی |

ابزارهای MCP بالا میان چند دستیار مشترک‌اند، اما محل تنظیم و شیوه احراز هویت هر کلاینت فرق دارد. مهارت مخصوص یک دستیار را بدون بررسی سازگاری در دستیار دیگر نصب نکنید.

## کاهش مصرف توکن و مدیریت زمینه

| پروژه | روش کمک | محدودیت |
|---|---|---|
| [RTK — فورک](https://github.com/opswithmorteza/rtk) · [اصلی](https://github.com/rtk-ai/rtk) | فیلتر خروجی Git، تست‌ها و فرمان‌های پشتیبانی‌شده | درصد کاهش خروجی فرمان، معادل کاهش کل مصرف یک کار نیست |
| [Headroom — فورک](https://github.com/opswithmorteza/headroom) · [اصلی](https://github.com/headroomlabs-ai/headroom) | فشرده‌سازی خروجی ابزارها، لاگ و داده‌های بازیابی‌شده | به ادغام فنی نیاز دارد؛ اثر را روی کار واقعی بسنجید |
| [Serena — فورک](https://github.com/opswithmorteza/serena) · [اصلی](https://github.com/oraios/serena) | بازیابی بخش مرتبط کد به‌جای خواندن فایل‌های کامل | مزیت به زبان و اندازه پروژه بستگی دارد |
| [QMD — فورک](https://github.com/opswithmorteza/qmd) · [اصلی](https://github.com/tobi/qmd) | جست‌وجوی محلی مستندات و یادداشت‌ها | برای دانش متنی و بازیابی انتخابی مناسب است |
| [Repomix — فورک](https://github.com/opswithmorteza/repomix) · [اصلی](https://github.com/yamadashy/repomix) | انتخاب فایل، شمارش توکن و استخراج ساختار فشرده کد | ارسال کل مخزن بدون فیلتر می‌تواند مصرف را بیشتر کند |
| [LLMLingua — فورک](https://github.com/opswithmorteza/LLMLingua) · [اصلی](https://github.com/microsoft/LLMLingua) | فشرده‌سازی پرامپت با مدل کوچک‌تر | بیشتر برای ساخت برنامه API؛ پلاگین آماده Codex نیست |

معیار درست: مصرف کل تا رسیدن به نتیجه صحیح. فشرده‌سازی شدید ممکن است موجب حذف اطلاعات، تکرار کار و افزایش هزینه شود. درصدهای تبلیغ‌شدهٔ پروژه‌ها تضمین صرفه‌جویی برای پروژه شما نیستند.

## حافظه ماندگار؛ Graphiti و گزینه‌های مشابه

| ابزار | کاربرد | مناسب چه کسی است؟ |
|---|---|---|
| [Graphiti — فورک](https://github.com/opswithmorteza/graphiti) · [اصلی](https://github.com/getzep/graphiti) | گراف دانش با رابطه‌ها و تغییرات زمانی | پروژه‌های طولانی که حفظ تصمیم‌ها و ارتباط اطلاعات مهم است |
| [Mem0 — فورک](https://github.com/opswithmorteza/mem0) · [اصلی](https://github.com/mem0ai/mem0) | لایه حافظه برای عامل‌ها و برنامه‌های AI | سازندگان برنامه‌های دارای حافظه کاربر یا عامل |
| [Supermemory — فورک](https://github.com/opswithmorteza/supermemory) · [اصلی](https://github.com/supermemoryai/supermemory) | ذخیره و بازیابی زمینه | برنامه‌هایی که به حافظه و جست‌وجوی اطلاعات نیاز دارند |

Graphiti می‌تواند اطلاعات مرتبط را به‌جای تاریخچه کامل بازیابی کند، اما استخراج، ذخیره و جست‌وجو نیز هزینه دارند. اتصال آن به دستیار به راه‌اندازی و یکپارچه‌سازی جداگانه نیاز دارد؛ صرف وجود این مخزن مصرف Codex یا Claude را کاهش نمی‌دهد.

## ساخت سایت و اپلیکیشن وب

| پروژه | نوع | کاربرد |
|---|---|---|
| [Next.js — فورک](https://github.com/opswithmorteza/next.js) · [اصلی](https://github.com/vercel/next.js) | چارچوب React | سایت و اپلیکیشن وب با کدنویسی |
| [bolt.diy — فورک](https://github.com/opswithmorteza/bolt.diy) · [اصلی](https://github.com/stackblitz-labs/bolt.diy) | محیط ساخت وب با AI | ساخت و ویرایش برنامه با دستور متنی |
| [GrapesJS — فورک](https://github.com/opswithmorteza/grapesjs) · [اصلی](https://github.com/GrapesJS/grapesjs) | چارچوب ویرایشگر بصری | ساخت صفحه‌ساز و ویرایشگر قالب |
| [Webstudio — فورک](https://github.com/opswithmorteza/webstudio) · [اصلی](https://github.com/webstudio-is/webstudio) | سایت‌ساز بصری | طراحی سایت با رابط گرافیکی |

## کتابخانه‌های رابط کاربری؛ قابل استفاده با Codex و Claude

این ابزارها داخل پروژه نصب می‌شوند؛ افزونه دستیار نیستند. می‌توانید از دستیار بخواهید رابط را با یکی از آن‌ها پیاده‌سازی کند.

| پروژه | مناسب برای |
|---|---|
| [Bootstrap — فورک](https://github.com/opswithmorteza/bootstrap) · [اصلی](https://github.com/twbs/bootstrap) | چیدمان واکنش‌گرا و اجزای عمومی HTML/CSS |
| [Ant Design — فورک](https://github.com/opswithmorteza/ant-design) · [اصلی](https://github.com/ant-design/ant-design) | پنل مدیریت و نرم‌افزارهای سازمانی React |
| [Material UI — فورک](https://github.com/opswithmorteza/material-ui) · [اصلی](https://github.com/mui/material-ui) | اجزای React با زبان طراحی Material |
| [shadcn/ui — فورک](https://github.com/opswithmorteza/ui) · [اصلی](https://github.com/shadcn-ui/ui) | رابط React با اجزای قابل شخصی‌سازی |

## طراحی UI/UX و مستندسازی

| پروژه | کاربرد |
|---|---|
| [Penpot — فورک](https://github.com/opswithmorteza/penpot) · [اصلی](https://github.com/penpot/penpot) | طراحی رابط و نمونه‌سازی تیمی |
| [Excalidraw — فورک](https://github.com/opswithmorteza/excalidraw) · [اصلی](https://github.com/excalidraw/excalidraw) | وایرفریم اولیه، دیاگرام و ایده‌پردازی |
| [Storybook — فورک](https://github.com/opswithmorteza/storybook) · [اصلی](https://github.com/storybookjs/storybook) | نمایش، مستندسازی و آزمایش مستقل اجزای رابط |
| [UI UX Pro Max — فورک](https://github.com/opswithmorteza/ui-ux-pro-max-skill) · [اصلی](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill) | مهارت راهنمای طراحی برای دستیارهای سازگار |

## دستیارهای مستقل کدنویسی

این‌ها جایگزین یا محیط جداگانه‌اند؛ نصب آن‌ها به معنی اضافه‌شدن پلاگین به Codex نیست.

- [OpenCode — فورک](https://github.com/opswithmorteza/opencode) · [اصلی](https://github.com/anomalyco/opencode): دستیار متن‌باز کدنویسی.
- [Codex — فورک](https://github.com/opswithmorteza/codex) · [اصلی](https://github.com/openai/codex): مخزن ابزار خط فرمان OpenAI.
- [Gemini CLI — فورک](https://github.com/opswithmorteza/gemini-cli) · [اصلی](https://github.com/google-gemini/gemini-cli): دستیار خط فرمان Gemini.
- [OpenHands — فورک](https://github.com/opswithmorteza/OpenHands) · [اصلی](https://github.com/OpenHands/OpenHands): پلتفرم عامل‌های توسعه نرم‌افزار.
- [Cline — فورک](https://github.com/opswithmorteza/cline) · [اصلی](https://github.com/cline/cline): عامل کدنویسی برای ویرایشگر و محیط‌های دیگر.
- [Continue — فورک](https://github.com/opswithmorteza/continue) · [اصلی](https://github.com/continuedev/continue): ابزار متن‌باز دستیار کدنویسی.
- [Aider — فورک](https://github.com/opswithmorteza/aider) · [اصلی](https://github.com/Aider-AI/aider): دستیار کدنویسی در ترمینال.

## فهرست‌های کشف ابزار

- [Awesome MCP Servers — فورک](https://github.com/opswithmorteza/awesome-mcp-servers) · [اصلی](https://github.com/punkpeye/awesome-mcp-servers): فهرست اتصال‌های MCP.
- [MCP Reference Servers — فورک](https://github.com/opswithmorteza/servers) · [اصلی](https://github.com/modelcontextprotocol/servers): سرورهای مرجع پروتکل MCP.

## انتخاب بر اساس سناریو

| هدف | ترکیب پیشنهادی برای ارزیابی |
|---|---|
| طراحی سایت با Codex یا Claude Code | Next.js + یکی از کتابخانه‌های UI + Context7 + Playwright MCP |
| کار روی مخزن بزرگ | Serena + جست‌وجوی هدفمند + RTK |
| مرور اولیه پروژه | Repomix با انتخاب فایل و شمارش توکن |
| حفظ تصمیم‌های پروژه در بلندمدت | ارزیابی Graphiti یا Mem0 با ادغام اختصاصی |
| طراحی بصری پیش از پیاده‌سازی | Penpot + Excalidraw |

## محبوبیت و فورک‌ها

انتخاب اولیه این فهرست با توجه به ارتباط کاربردی و پروژه‌های دارای فورک قابل توجه انجام شده است؛ رتبه‌بندی جامع گیت‌هاب نیست. تعداد فورک تغییر می‌کند و به‌تنهایی معیار کیفیت یا صرفه‌جویی نیست. برای آمار زنده روی لینک پروژه اصلی کلیک کنید.

## مشارکت و مجوز

برای پیشنهاد ابزار، اصلاح توضیح یا گزارش لینک خراب، Issue یا Pull Request باز کنید. کاربرد، کلاینت سازگار، روش نصب رسمی و محدودیت‌ها را ذکر کنید.

متن تألیفی این راهنما تحت [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/) برای استفاده و بازنشر آزاد ارائه می‌شود. کد، نام تجاری و محتوای پروژه‌های لینک‌شده تابع مجوز و شرایط خود آن پروژه‌هاست. این فهرست وابسته یا مورد تأیید رسمی صاحبان ابزارها نیست.


## استفاده و به‌روزرسانی فورک‌ها

۳۳ فورک عمومی در تاریخ ۲۰۲۶-۱۱-۰۳ بررسی شدند. فورک، نسخه‌ای مستقل از کد پروژه در این حساب است؛ به‌معنی نصب یا فعال‌سازی ابزار در Codex یا Claude نیست.

برای دریافت تغییرات جدید، در صفحه فورک گزینه **Sync fork → Update branch** را بررسی کنید. فورک‌ها به‌صورت خودکار همگام نمی‌شوند. برای نصب و اجرای هر ابزار، README و مجوز همان پروژه را بخوانید؛ مجوز متن این راهنما مجوز کد پروژه‌های دیگر را تغییر نمی‌دهد.
