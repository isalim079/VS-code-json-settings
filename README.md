# VS-code-json-settings



{
  "liveServer.settings.CustomBrowser": "chrome",
  "terminal.integrated.fontSize": 20,
  "files.autoSave": "afterDelay",
  "workbench.iconTheme": "vscode-icons",
  "editor.minimap.enabled": false,
  "editor.fontLigatures": true,
  "editor.fontVariations": false,

  // "editor.fontFamily": "  Fira Code,  JetBrain ", 
  "editor.fontFamily": " Operator Mono Light, OperatorMonoLig-BookItalic, Fira Code, JetBrains,  Operator Mono", 

// sumit

"editor.tokenColorCustomizations": {
  "textMateRules": [
    {
      "scope": [
        //following will be in italic
        "comment",
        "emphasis",
        "entity.other.attribute-name",  
        // "entity.name.method.js",
        // "entity.name.class.js",
        // "entity.name.tag.doctype",
        // "entity.other.attribute-name.tag.jade",
        // "entity.other.attribute-name.tag.pug",
        // "keyword",
        // "keyword.control",
        // "keyword.operator.comparison",
        // "keyword.control.flow.js",
        // "keyword.control.flow.ts",
        // "keyword.control.flow.tsx",
        // "keyword.control.ruby",
        // "keyword.control.module.ruby",
        // "keyword.control.class.ruby",
        // "keyword.control.def.ruby",
        // "keyword.control.loop.js",
        // "keyword.control.loop.ts",
        // "keyword.control.import.js",
        // "keyword.control.import.ts",
        // "keyword.control.import.tsx",
        // "keyword.control.from.js",
        // "keyword.control.from.ts",
        // "keyword.control.from.tsx",
        // "keyword.operator.expression.delete",
        // "keyword.operator.new",
        // "keyword.operator.expression",
        // "keyword.operator.cast",
        // "keyword.operator.relational",
        // "keyword.operator.sizeof",
        // "keyword.operator.logical.python",
        // "italic",
        // "markup.italic",
        // "markup.quote",
        // "markup.changed",
        // "markup.italic.markdown",
        // "markup.quote.markdown",
        // "markup.deleted.diff",
        // "markup.inserted.diff",
        // "meta.delimiter.period",
        // "meta.diff.header.git",
        // "meta.diff.header.from-file",
        // "meta.diff.header.to-file",
        // "meta.tag.sgml.doctype",
        // "meta.var.expr",
        // "meta.class meta.method.declaration meta.var.expr storage.type.js",
        // "meta.decorator punctuation.decorator",
        // "meta.selector",
        // "punctuation.accessor",
        // "punctuation.definition.comment",
        // "punctuation.definition.template-expression.begin",
        // "punctuation.definition.template-expression.end",
        // "punctuation.section.embedded",
        // "quote",
        // "source.js constant.other.object.key.js string.unquoted.label.js",
        // "source.go keyword.package.go",
        // "source.go keyword.import.go",
        // "source.go keyword.function.go",
        // "source.go keyword.type.go",
        // "source.go keyword.struct.go",
        // "source.go keyword.interface.go",
        // "source.go keyword.const.go",
        // "source.go keyword.var.go",
        // "source.go keyword.map.go",
        // "source.go keyword.channel.go",
        // "source.go keyword.control.go",
        // "storage",
        // "storage.type",
        // "storage.modifier",
        // "storage.type.property.js",
        // "storage.type.property.ts",
        // "storage.type.property.tsx",
        // "tag.decorator.js entity.name.tag.js",
        // "tag.decorator.js",
        // "text.html.basic entity.other.attribute-name.html",
        // "text.html.basic entity.other.attribute-name",
        // "variable.language",
        // "variable.other.object.property"
      ],
      "settings": {
       
        "fontStyle": "italic"
      }
    }
  ]
},
  
  "editor.cursorSmoothCaretAnimation": "on", // sumit dada settings

  /* sumit end */

  "editor.cursorBlinking": "expand",
  "[html]": {
    "editor.defaultFormatter": "vscode.html-language-features"
  },
  "[javascriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "prettier.tabWidth": 4,
  "[css]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[json]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "cSpell.userWords": [
    "Swal"
  ],
  "workbench.colorTheme": "Andromeda Colorizer",
  "editor.fontSize": 17,
  "notebook.editorOptionsCustomizations": {

  },
  // "workbench.colorCustomizations": {

  // },
  
    // Controls whether bracket pair colorization is enabled or not. Use 'workbench.colorCustomizations' to override the bracket highlight colors.
    "editor.bracketPairColorization.enabled": true,
    // Controls whether the editor should render indent guides.
    "editor.guides.indentation": true,
    // Controls whether bracket pair guides are enabled or not.
    //  - true: Enables bracket pair guides.
    //  - active: Enables bracket pair guides only for the active bracket pair.
    //  - false: Disables bracket pair guides.
    "editor.guides.bracketPairs": "active",
    // Controls whether horizontal bracket pair guides are enabled or not.
    //  - true: Enables horizontal guides as addition to vertical bracket pair guides.
    //  - active: Enables horizontal guides only for the active bracket pair.
    //  - false: Disables horizontal bracket pair guides.
    "editor.guides.bracketPairsHorizontal": "active",
    // Controls whether the editor should highlight the active indent guide.
    "editor.guides.highlightActiveIndentation": true,
    // Controls whether bracket pair guides are enabled or not.
    "editor.guides.highlightActiveBracketPair": true,
    // Defines the bracket symbols that increase or decrease the indentation.
    "editor.language.brackets": [
      ["[", "]"],
      ["(", ")"],
      ["{", "}"]
    ],
    // Defines the bracket pairs that are colorized by their nesting level if bracket pair colorization is enabled.
    "editor.language.colorizedBracketPairs": [
      ["[", "]"],
      ["(", ")"],
      ["{", "}"]
    ],
    "workbench.colorCustomizations": {
      "editorBracketHighlight.foreground1": "#fac928",
      "editorBracketHighlight.foreground2": "#c122e9",
      "editorBracketHighlight.foreground3": "#057aff",
      "editorBracketHighlight.foreground4": "#00e74d",
      "editorBracketHighlight.foreground5": "#f51384",
      "editorBracketHighlight.foreground6": "#19f9d8",
      "editorBracketPairGuide.background1": "#fac9289E",
      "editorBracketPairGuide.background2": "#c122e99E",
      "editorBracketPairGuide.background3": "#057aff9E",
      "editorBracketPairGuide.background4": "#00e74d9E",
      "editorBracketPairGuide.background5": "#f513849E",
      "editorBracketPairGuide.background6": "#19f9d89E",
      "editorBracketPairGuide.activeBackground1": "#FAC9289E",
      "editorBracketPairGuide.activeBackground2": "#C122E99E",
      "editorBracketPairGuide.activeBackground3": "#057AFF9E",
      "editorBracketPairGuide.activeBackground4": "#00E7499E",
      "editorBracketPairGuide.activeBackground5": "#F513849E",
      "editorBracketPairGuide.activeBackground6": "#19F9D89E",
    },
    "emmet.includeLanguages": {
      "javascript": "javascriptreact"
    },
    "terminal.integrated.env.windows": {},
    "console-ninja.featureSet": "Community",
    // "files.associations": {
    //   "*.js": "javascriptreact"
    // }
  
  
}


