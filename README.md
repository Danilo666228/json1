# json1
json


{
	// Основные настройки редактора
	"window.openFilesInNewWindow": "off",
	"editor.tabSize": 3,
	"editor.folding": false,
	"editor.insertSpaces": false,
	"editor.smoothScrolling": true,
	"editor.minimap.enabled": false,
	"editor.detectIndentation": true,
	"editor.suggestSelection": "first",
	"editor.multiCursorModifier": "ctrlCmd",

	// Настройки переноса слов
	"editor.wordWrap": "bounded",
	"editor.wrappingIndent": "same",
	"editor.wordWrapColumn": 130,

	// Прокрутка за пределы последней строки
	"editor.scrollBeyondLastLine": true,

	// Связанные редактирования тегов
	"editor.linkedEditing": true,

	// Автоматическое закрытие тегов
	"html.autoClosingTags": true,
	"javascript.autoClosingTags": true,
	"typescript.autoClosingTags": true,

	// Отображение символов
	"editor.renderControlCharacters": false,

	// Подсветка неоднозначных символов
	"editor.unicodeHighlight.ambiguousCharacters": false,

	// Быстрые подсказки
	"html.completion.attributeDefaultValue": "singlequotes",

	// Внешний вид
	"editor.bracketPairColorization.enabled": false,
	"editor.glyphMargin": false,
	"editor.scrollbar.horizontal": "hidden",
	"editor.scrollbar.vertical": "hidden",
	"workbench.productIconTheme": "fluent-icons",
	"window.density.editorTabHeight": "compact",
	"editor.accessibilitySupport": "off",
	"symbols.hidesExplorerArrows": false,
	"workbench.iconTheme": "vscode-jetbrains-icon-theme-2023-dark",
	"workbench.layoutControl.enabled": false,
	"workbench.editor.editorActionsLocation": "titleBar",
	"workbench.editor.empty.hint": "hidden",
	"fonted.font": "JetBrains Mono",
	// Настройки курсора
	"editor.cursorBlinking": "expand",
	"editor.cursorStyle": "line-thin",
	"editor.cursorSmoothCaretAnimation": "explicit",

	// Настройки шрифта
	// "editor.fontSize": 18,
	"editor.fontSize": 13.5,
	"editor.lineHeight": 22.5,
	"editor.fontWeight": "400",
	"editor.fontLigatures": true,
	"editor.fontFamily": "Cascadia Code, Fira Code, PragmataPro Mono Liga, JetBrains Mono, Maple Mono, IBM Plex Mono, MonoLisa, Ubuntu Mono, Geist Mono, Fira Code iScript, DejaVu Sans Mono, Sarala, monospace",
	"editor.inlayHints.fontFamily": "Cascadia Code",
	"chat.editor.fontFamily": "Cascadia Code",
	"editor.codeLensFontFamily": "Cascadia Code",
	"debug.console.fontFamily": "Cascadia Code",

	// Кастомизация подсветки синтаксиса
	"editor.tokenColorCustomizations": {
		"textMateRules": [
			{
				"scope": [
					"comment",
					"entity.name.type.class",
					"keyword",
					"constant",
					"storage.modifier",
					"storage.type.class.js"
				],
				"settings": {
					"fontStyle": "italic"
				}
			},
			{
				"scope": [
					"invalid",
					"keyword.operator",
					"constant.numeric.css",
					"keyword.other.unit.px.css",
					"constant.numeric.decimal.js",
					"constant.numeric.json"
				],
				"settings": {
					"fontStyle": ""
				}
			}
		]
	},

	// Настройки терминала
	"terminal.integrated.fontFamily": "Cascadia Code",
	"terminal.integrated.fontSize": 13,
	"terminal.integrated.tabs.enabled": false,
	"terminal.integrated.cursorStyle": "line",

	// Настройки обозревателя
	"explorer.confirmDelete": false,
	"explorer.confirmDragAndDrop": false,
	"explorer.compactFolders": false,
	"workbench.editor.tabSizing": "fit",
	"workbench.startupEditor": "newUntitledFile",

	// Настройки отладки
	"debug.toolBarLocation": "hidden",
	"debug.focusWindowOnBreak": false,
	"debug.showInlineBreakpointCandidates": false,
	"debug.showBreakpointsInOverviewRuler": false,

	// Настройки Emmet
	"emmet.includeLanguages": {
		"blade": "html",
		"javascript": "javascriptreact"
	},
	"emmet.triggerExpansionOnTab": true,

	// Настройки форматирования

	"prettier.semi": false,
	"prettier.useTabs": true,
	"editor.formatOnSave": true,
	"prettier.singleQuote": true,
	"prettier.jsxSingleQuote": true,
	"editor.codeActionsOnSave": {
		"source.organizeImports": "explicit"
	},
	"[prisma]": {
		"editor.defaultFormatter": "Prisma.prisma"
	},
	"prettier.arrowParens": "avoid",
	"editor.defaultFormatter": "esbenp.prettier-vscode",
	"editor.inlineSuggest.enabled": true,

	// Настройки для Laravel
	"[blade]": {
		"editor.defaultFormatter": "onecentlin.laravel-blade"
	},

	// Настройки для Breadcrumbs
	"breadcrumbs.icons": false,
	"breadcrumbs.showKeys": false,
	"breadcrumbs.showFiles": false,
	"breadcrumbs.symbolPath": "off",
	"breadcrumbs.showArrays": false,
	"breadcrumbs.showEvents": false,
	"breadcrumbs.showFields": false,
	"breadcrumbs.showClasses": false,
	"breadcrumbs.showMethods": false,
	"breadcrumbs.showBooleans": false,
	"breadcrumbs.showFunctions": false,
	"breadcrumbs.showConstants": false,
	"breadcrumbs.showEnumMembers": false,
	"breadcrumbs.showConstructors": false,

	// Настройки для JS и TS
	"javascript.updateImportsOnFileMove.enabled": "always",
	"typescript.updateImportsOnFileMove.enabled": "always",
	"typescript.preferences.quoteStyle": "single",
	"javascript.preferences.quoteStyle": "single",
	"javascript.format.semicolons": "remove",
	"typescript.format.semicolons": "remove",
	"js/ts.implicitProjectConfig.experimentalDecorators": true,

	// Настройки проверки орфографии
	"cSpell.language": "en,ru",
	"cSpell.enabled": true,
	"cSpell.enableFiletypes": [
		"blade",
		"jsx",
		"tsx",
		"ts",
		"js",
		"scss",
		"sass",
		"vue"
	],

	// Разрешенные символы для Unicode Highlight
	"editor.unicodeHighlight.allowedCharacters": {
		"а": true,
		"с": true,
		"Т": true,
		"б": true,
		"е": true,
		" ": true
	},
	"editor.hideCursorInOverviewRuler": true,
	"git.enableSmartCommit": true,

	// Исключаемые файлы
	"files.exclude": {
		"**/.expo": true,
		"**/.expo-shared": true,
		"**/.idea": true,
		"**/.nuxt": true
	},

	// Прочие настройки
	"files.defaultLanguage": "plaintext",
	"diffEditor.ignoreTrimWhitespace": false,
	"security.workspace.trust.untrustedFiles": "open",
	"vsintellicode.modify.editor.suggestSelection": "automaticallyOverrodeDefaultValue",
	"window.confirmBeforeClose": "keyboardOnly",
	"git.openRepositoryInParentFolders": "never",
	"editor.gotoLocation.multipleDefinitions": "goto",
	"window.zoomLevel": 0,
	"editor.stickyScroll.scrollWithEditor": false,
	"workbench.tree.enableStickyScroll": false,
	"editor.stickyScroll.enabled": false,
	"redhat.telemetry.enabled": false,
	"github.copilot.editor.enableAutoCompletions": true,
	"window.commandCenter": false,
	"workbench.editor.customLabels.patterns": {
		"**/app/**/[[]*[]]/[[]*[]]/page.tsx": "${dirname(2)}/${dirname(1)}/${dirname}/page.tsx",
		"**/app/**/[[]*[]]/page.tsx": "${dirname(1)}/${dirname}/page.tsx",
		"**/app/**/page.tsx": "${dirname}/page.tsx",
		"**/app/**/[[]*[]]/[[]*[]]/layout.tsx": "${dirname(2)}/${dirname(1)}/${dirname}/layout.tsx",
		"**/app/**/[[]*[]]/layout.tsx": "${dirname(1)}/${dirname}/layout.tsx",
		"**/app/**/layout.tsx": "${dirname}/layout.tsx"
	},
	"cSpell.userWords": ["clsx", "recaptcha", "sitekey", "testid"],
	"markdown.updateLinksOnFileMove.enabled": "always",
	"javascript.experimental.updateImportsOnPaste": true,
	"typescript.experimental.updateImportsOnPaste": true,
	"markdown.experimental.updateLinksOnPaste": true,
	"cSpell.autoFormatConfigFile": true,
	"workbench.statusBar.visible": true,
	"files.autoSave": "afterDelay",
	"codeium.enableCodeLens": false,
	"workbench.colorTheme": "Default Dark+",
	"update.mode": "manual",
	"codeium.enableConfig": {
		"*": true,
		"prisma": true,
		"properties": true,
		"snippets": true
	},
	"todohighlight.isEnable": false
}
