# МТ — публичная фиксация хешей / MT scientific hash records

**Автор / Author:** Широков Дмитрий Юрьевич.

**Выпуск / Edition:** `v0p5`, статус / status: `canon_draft`.

## Русская версия

Эта запись публикует SHA-256 подготовленного научного архива теории
материальной точки и его зашифрованного контейнера. Сам научный архив,
математические тексты, вычислительные данные и ключ расшифрования здесь
не размещены.

| Объект | Имя файла | Точный размер, байт |
|---|---|---:|
| Исходный научный архив | `MT_SCIENTIFIC_v0p5_20260924.tar.zst` | 11944268913 |
| Зашифрованный контейнер | `MT_SCIENTIFIC_v0p5_20260924.tar.zst.gpg` | 11945775777 |

**SHA-256 исходного научного архива:**

```text
3a0e47d6bf168fc5e94b9cb83af2ade6ac40857646607ebcb0be297e298a68a4
```

**SHA-256 зашифрованного контейнера:**

```text
7a86da8a13f31924d2f4af3c0ae192767b385cedf79be61ac8fa63041deb80af
```

Машиночитаемые сведения: [manifest.json](manifest.json).
Список контрольных сумм: [SHA256SUMS](SHA256SUMS).

Полное локальное расшифрование проверено: хеш восстановленных байтов
совпадает с хешем исходного архива. Хеш исходного архива относится к точным
байтам TAR.ZST; перепаковка может изменить его. Повторное шифрование также
создаст другой хеш контейнера, даже при неизменном научном архиве.

Дата `2026-09-24` в имени — обозначение архивного комплекта. Время локальной
подготовки приведено в manifest.json и не является независимой временной
отметкой публикации. Эта запись сама по себе не подтверждает научную
корректность, новизну или авторство и не заменяет раскрытия содержания
научной статьи. Статус `canon_draft` сохраняется.

## English version

This record publishes the SHA-256 hashes of the prepared Material Point
Theory (MT) scientific archive and its encrypted container. Neither archive,
scientific contents, computational data, nor the decryption key is hosted here.
The exact filenames, byte counts and hashes are listed above and in
[manifest.json](manifest.json) and [SHA256SUMS](SHA256SUMS).

Full local decryption was verified against the plaintext archive hash.
The plaintext hash identifies the exact TAR.ZST bytes; repackaging may change
it. Re-encrypting unchanged plaintext will produce a different container hash.

The date `2026-09-24` in the filenames labels the archive package. The local
preparation time in the manifest is not an independent publication timestamp.
This hash record alone does not establish scientific correctness, novelty,
or authorship, and does not replace disclosure of the scientific work.
The edition retains its `canon_draft` status.
