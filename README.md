# 🎬 CSV to Social Reel Captions 

A lightning-fast, zero-dependency visual web utility built to mass-generate structured social media titles, captions, and dynamic hashtags straight from any columnized CSV dataset. 

Perfect for sports content creators, social media managers, and digital marketers preparing bulk video publishing streams.

## ✨ Features

- **📂 100% Client-Side Parsing:** Powered by `PapaParse`. Your corporate datasets never touch an external server; all operations parse locally instantly inside your browser.
- **⚡ Reactive Live Preview Panel:** Watch titles, description copies, and hashtag structures render dynamically over your layout choices as you type.
- **🏷️ Automated Smart Hashtags:** Automatically exposes a duplicate `#` modifier for every spreadsheet column header, stripping out spaces, capitals, and punctuation characters (`{country}` ➡️ `{country_hashtag}`).
- **🔍 Variable Quick-Filtering:** Type and sort your database mapping variables in real-time to find data keys instantly.
- **🛡️ Character Encoding Safety:** Explicitly configured with plain text components to prevent Excel character corruptions or platform rendering failures.

## 🚀 Quick Start

1. **Download App File:** Copy the code saved in `app.html` onto your machine.
2. **Launch Application:** Open `app.html` directly inside any modern desktop web browser (Chrome, Edge, Safari, Firefox).
3. **Upload Dataset Matrix:** Select or drop your raw target enriched source CSV sheet.
4. **Build Custom Copy Patterns:** - Click variable cards from **Step 2** to copy dynamic tags onto your clipboard.
   - Paste them into **Step 3**'s title and description field configurations.
5. **Download Final File:** Tap **Download Clean CSV** to pull down your unified structural layout ready for immediate scheduling apps.

## 🛠️ Syntactical References

The template processing engine supports two template token injection patterns:

| Variable Selector Type | Syntax Format | Visual Execution Conversion Example |
| :--- | :--- | :--- |
| **Standard String Data** | `{column_name}` | `Czech Republic` |
| **Social Media Safe Tag** | `{column_name}_hashtag` | `czechrepublic` |

### Concrete Usage Mapping Example:
```text
Title Layout   ->  {country} is rocking the fresh {kit_color_primary_name} kits!
Caption Layout ->  Representing {continent}! Led by manager {coach_name}. #{country_hashtag}
