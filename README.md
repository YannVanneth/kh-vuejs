# vuejs.org កំណែជាភាសាខ្មែរ

## ការរួមចំណែក

គេហទំព័រនេះត្រូវបានបង្កើតឡើងជាមួយ [VitePress](https://github.com/vuejs/vitepress) និងអាស្រ័យលើ [@vue/theme](https://github.com/vuejs/vue-theme)។ ខ្លឹមសារនៃគេហទំព័រត្រូវបានសរសេរជាទម្រង់ Markdown ដែលមានទីតាំងនៅក្នុង `src`។ សម្រាប់ការកែសម្រួលសាមញ្ញ អ្នកអាចកែសម្រួលឯកសារដោយផ្ទាល់នៅលើ GitHub និងបង្កើត Pull Request ។

សម្រាប់ local development [pnpm](https://pnpm.io/) ត្រូវបានជ្រើសជា package manager៖

```bash
pnpm i
pnpm run dev
```

គម្រោងនេះតម្រូវឱ្យ Node.js មានកំណែ `v18` ឬខ្ពស់ជាងនេះ។ ហើយវាត្រូវបានណែនាំអោយបើកនូវ corepack៖

```bash
corepack enable
```

## ការធ្វើការលើ​ Content

- សូមមើលឯកសារ VitePress នៅលើ [Markdown Extensions](https://vitepress.dev/guide/markdown) ដែលគាំទ្រ និងសមត្ថភាពក្នុងការ [ការប្រើ Vue syntax នៅខាងក្នុង markdown](https://vitepress.dev/guide/using-vue)។

- សូមមើល [Writing Guide](https://github.com/vuejs/docs/blob/main/.github/contributing/writing-guide.md) សម្រាប់ច្បាប់ និងអនុសាសន៍របស់យើងលើការសរសេរ និងរក្សាខ្លឹមសារឯកសារ។
  
## ការធ្វើការលើ theme

ប្រសិនបើការផ្លាស់ប្តូរត្រូវបានបង្កើតឡើងសម្រាប់ theme សូមពិនិត្យមើល [ការណែនាំសម្រាប់ការអភិវឌ្ឍន៍ theme ជាមួយឯកសារ](https://github.com/vuejs/vue-theme#developing-with-real-content)។
