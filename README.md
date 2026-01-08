# rime-latin

**Litterae Latīnae Macrōnātae prō Rime | Latin Macron Input for Rime | 中州韻拉丁語長音輸入方案**

---

## De hōc projectō

Rime-configūrātiō prō litterīs Latīnīs cum macrōnibus (ā, ē, ī, ō, ū, ȳ), brevibus (ă, ĕ, ĭ, ŏ, ŭ, y̆), et nexibus (æ, œ).

---

## English

### About

A Rime input schema for typing Latin diacritical marks, designed for Latin learners:

-   **Macron** (long vowels): ā, ē, ī, ō, ū, ȳ
-   **Breve** (short vowels): ă, ĕ, ĭ, ŏ, ŭ, y̆
-   **Ligatures**: æ, œ

### Input Methods

> 💡 The case of the output follows the first letter: `aA` → ā, `Aa` → Ā

#### Macron

| Input       | Output | Input       | Output |
| ----------- | ------ | ----------- | ------ |
| `a-` / `aa` | ā      | `A-` / `AA` | Ā      |
| `e-` / `ee` | ē      | `E-` / `EE` | Ē      |
| `i-` / `ii` | ī      | `I-` / `II` | Ī      |
| `o-` / `oo` | ō      | `O-` / `OO` | Ō      |
| `u-` / `uu` | ū      | `U-` / `UU` | Ū      |
| `y-` / `yy` | ȳ      | `Y-` / `YY` | Ȳ      |

#### Breve

| Input | Output | Input | Output |
| ----- | ------ | ----- | ------ |
| `a\`` | ă      | `A\`` | Ă      |
| `e\`` | ĕ      | `E\`` | Ĕ      |
| `i\`` | ĭ      | `I\`` | Ĭ      |
| `o\`` | ŏ      | `O\`` | Ŏ      |
| `u\`` | ŭ      | `U\`` | Ŭ      |
| `y\`` | y̆      | `Y\`` | Y̆      |

#### Ligatures

| Input         | Output | Input         | Output |
| ------------- | ------ | ------------- | ------ |
| `aee` / `ae-` | æ      | `AEE` / `AE-` | Æ      |
| `oee` / `oe-` | œ      | `OEE` / `OE-` | Œ      |

> 💡 To type literal `ae` or `oe`, just type them — they will output as-is unless followed by `e` or `-`.

### Installation

1. Copy `latin.schema.yaml` and `latin.dict.yaml` to your Rime user directory:

    - **macOS (Squirrel)**: `~/Library/Rime/`
    - **Windows (Weasel)**: `%APPDATA%\Rime\`
    - **Linux (ibus-rime)**: `~/.config/ibus/rime/`

2. Add `latin` to your schema list in `default.custom.yaml`:

```yaml
patch:
    schema_list:
        - schema: latin
        # ... your other schemas
```

3. Redeploy Rime

### License

MIT

---

## 中文

### 簡介

這是一個為拉丁語學習者設計的中州韻輸入方案，用於輸入：

-   **長音符 Macron**：ā, ē, ī, ō, ū, ȳ
-   **短音符 Breve**：ă, ĕ, ĭ, ŏ, ŭ, y̆
-   **合字 Ligatures**：æ, œ

### 輸入方式

> 💡 輸出的大小寫以第一個字母為準：`aA` → ā，`Aa` → Ā

#### 長音符

| 輸入        | 輸出 | 輸入        | 輸出 |
| ----------- | ---- | ----------- | ---- |
| `a-` / `aa` | ā    | `A-` / `AA` | Ā    |
| `e-` / `ee` | ē    | `E-` / `EE` | Ē    |
| `i-` / `ii` | ī    | `I-` / `II` | Ī    |
| `o-` / `oo` | ō    | `O-` / `OO` | Ō    |
| `u-` / `uu` | ū    | `U-` / `UU` | Ū    |
| `y-` / `yy` | ȳ    | `Y-` / `YY` | Ȳ    |

#### 短音符

| 輸入  | 輸出 | 輸入  | 輸出 |
| ----- | ---- | ----- | ---- |
| `a\`` | ă    | `A\`` | Ă    |
| `e\`` | ĕ    | `E\`` | Ĕ    |
| `i\`` | ĭ    | `I\`` | Ĭ    |
| `o\`` | ŏ    | `O\`` | Ŏ    |
| `u\`` | ŭ    | `U\`` | Ŭ    |
| `y\`` | y̆    | `Y\`` | Y̆    |

#### 合字

| 輸入          | 輸出 | 輸入          | 輸出 |
| ------------- | ---- | ------------- | ---- |
| `aee` / `ae-` | æ    | `AEE` / `AE-` | Æ    |
| `oee` / `oe-` | œ    | `OEE` / `OE-` | Œ    |

> 💡 直接輸入 `ae` 或 `oe` 會原樣輸出，除非後面跟著 `e` 或 `-`。

### 安裝

1. 將 `latin.schema.yaml` 和 `latin.dict.yaml` 複製到 Rime 用戶目錄：

    - **macOS 鼠鬚管**: `~/Library/Rime/`
    - **Windows 小狼毫**: `%APPDATA%\Rime\`
    - **Linux ibus-rime**: `~/.config/ibus/rime/`

2. 在 `default.custom.yaml` 中加入方案：

```yaml
patch:
    schema_list:
        - schema: latin
        # ... 其他方案
```

3. 重新部署

### 授權

MIT
