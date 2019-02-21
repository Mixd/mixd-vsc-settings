```json
/**
 * Mixd VSC Settings
 *
 * Extensions used:
 * 1. phpcs - Used for guiding PSR-2 best practices (required)
 * 2. intelephense - Used for PHP intelligence and insights (required)
 * 3. docblockr - Used for generating sensible method/function documentation (required)
 * 4. phpfmt - Used for formatting automatically (optional)
 */
 {
    "html.format.endWithNewline": true,
    "files.exclude": {
        "**/.git": false,
        "**/.svn": true,
        "**/.hg": true,
        "**/CVS": true,
        "**/.DS_Store": true,
    },
    "files.insertFinalNewline": true,
    "files.trimFinalNewlines": true,
    "files.trimTrailingWhitespace": true,
    "phpcs.enable": true,
    "phpcs.standard": "PSR2",
    "phpcs.executablePath": "<path to>/.composer/vendor/bin/phpcs",
    "phpcs.ignorePatterns": [
        "*/wordpress/*",
        "*/content/plugins/*"
    ],
    "php.validate.executablePath": "<path to>/bin/php",
    "php.suggest.basic": false,
    "files.associations": {
        "*.svg": "html"
    },
    "intelephense.format.enable": false,
    "editor.rulers": [
        120
    ],
    "editor.renderWhitespace": "boundary",
    "docBlocker.defaultTpl": "/**  * @Author: {{author}}  * @Date: {{createTime}}  * @Desc: $0  */  ",
    "docBlocker.Author": "<your name here>",
    "phpfmt.indent_with_space": 4,
    "phpfmt.php_bin": "<path to>/bin/php",
    "phpfmt.psr2": true,
    "editor.formatOnPaste": false,
    "[php]": {
        "editor.formatOnSave": false
    },
    "breadcrumbs.enabled": false,
    "workbench.startupEditor": "newUntitledFile",
}

```
