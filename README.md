# Markdown PHP

A [Zed](https://zed.dev) extension that adds PHP syntax highlighting inside Markdown fenced code blocks without requiring `<?php` tags.

## Usage

Use a `php` fenced code block in any Markdown file:

````markdown
```php
$user = User::query()->find(1);

echo $user->name;
```
````

## Installation

Search for **Markdown PHP** in the Zed Extensions panel (`cmd+shift+x`).
