<h1 align="center" style="border-bottom: none">
    <b>
        <a href="https://www.nocodb.com">NocoDB</a><br>
    </b>
    ๐ ์คํ ์์ค Airtable ๋์ ๐ <br>
</h1>

<p align="center">
๋ชจ๋  MySQL, PostgreSQL, SQL Server, SQLite ๋ฐ MariaDB๋ฅผ ์ค๋งํธ ์คํ๋ ๋์ํธ๋ก ๋ณํํฉ๋๋ค.
</p>
<p align="center">
    <a href="http://www.nocodb.com"><b>Website</b></a> โข
    <a href="https://discord.gg/5RgZmkW"><b>Discord</b></a> โข
    <a href="https://twitter.com/nocodb"><b>Twitter</b></a> โข
    <a href="https://github.com/nocodb/nocodb"><b>GitHub</b></a> โข
    <a href="https://docs.nocodb.com/"><b>Documentation</b></a>
</p>

---------------------------------------------------------------------


# [v0.80.0](https://github.com/nocodb/nocodb/releases/tag/0.80.0) ๋ฆด๋ฆฌ์ค ๋ธํธ: FORM ๋ฐ GRID ๋ณด๊ธฐ
๋ ๋์ ํ ํ์์ ์ํ ๋ ๋ค๋ฅธ ๋จ๊ณ!
Noco VIEWs์ ํจ๊ป ์ํ๋ ๋ง์ถคํ ๋ฐ์ดํฐ๋ฅผ ์ํ๋ ๋ฐฉ์์ผ๋ก ๊ณต์ ํ๊ณ  ์์งํ์ธ์!

## GRID ๋ณด๊ธฐ
```**GRID ๋ณด๊ธฐ**```๋ ๋ค๋ฅธ ํ/์ฌ๋๊ณผ ์ ๋ณด ํ์ ์งํฉ์ ๊ณต์ ํ๋ ์ข์ ๋ฐฉ๋ฒ์๋๋ค. ๊ณต์  ๊ทธ๋ฆฌ๋ ๋ณด๊ธฐ๋ ์ฝ๊ธฐ ์ ์ฉ์๋๋ค. ๊ทํ์ ํ์ ์์ ํ ๋ฐ์ดํฐ๋ฒ ์ด์ค ์ก์ธ์ค์ ์ํฅ์ ๋ฏธ์น์ง ์์ผ๋ฉด์ ํ์ํ ์ ๋ณด์ ์ก์ธ์คํ  ์ ์์ต๋๋ค.

### ํน์ง
- ํ/๋์์ ๋ฐ๋ผ ํ์ด๋ธ ๋ฐ์ดํฐ๋ฅผ ๋ค๋ฅธ ๋ณด๊ธฐ๋ก ์ฌ์ฉ์ ์ ์
   - ์ด ํ์/์จ๊ธฐ๊ธฐ
   - ํ ํํฐ๋ง
   - ์ฝํ์ธ  ์ ๋ ฌ/์์
- ๊ณ ์ ํ ๊ทธ๋ฆฌ๋ ๋ณด๊ธฐ๋ฅผ ์ํ๋ ์๋งํผ ์์ฑ/๊ณต์ 
- ํญ์ ์๋ก ์์ํ๋ ๋์  ๊ธฐ์กด ๋ณด๊ธฐ๋ฅผ ์ ๋ณด๊ธฐ์ ๊ธฐ๋ฐ์ผ๋ก ๋ณต์ฌ
- ์ํธ๋ฅผ ์ฌ์ฉํ์ฌ ๊ณต์  ๋ณด๊ธฐ ์ก์ธ์ค ๋ณดํธ

### ์์ฑ, ์ฌ์ฉ์ ์ ์ ๋ฐ ๊ณต์  ๋ฐฉ๋ฒ
![Grid](https://user-images.githubusercontent.com/86527202/138726069-226dc0e6-4064-49d8-8a57-57ddd32009c3.gif)


------------------------------------------

## FORM ๋ณด๊ธฐ
```**FORM ๋ณด๊ธฐ**```๋ ๋ค๋ฅธ ์ฌ๋๋ค๋ก๋ถํฐ ์ ๋ณด๋ฅผ ์์งํ๊ณ  ๋ฐ์ดํฐ๋ฒ ์ด์ค์ ๊ธฐ๋กํ๊ณ  ๋ฐ์ดํฐ๋ฒ ์ด์ค ํ์ด๋ธ์ ๊ธฐ์กด ํ๋๋ฅผ ์ฌ์ฉํ์ฌ ์ฝ๊ฒ ์์ฑํ  ์ ์๋ ์ฌ์ด ์ก์ธ์ค๋ฅผ ์ ๊ณตํฉ๋๋ค.

### ํน์ง
- ํ์ํ ํ๋๋ฅผ ์ฝ๊ฒ ๋์ด์ ๋๊ธฐ๋ก ์์ ๋ณด๊ธฐ ์ฌ์ฉ์ ์ ์
- ํ๋ ๋ฐ์ดํฐ ํ์์ ๋ฐ๋ฅธ ๊ฒ์ฆ ์ง์
- ๊ณ ์ ํ ์์ ๋ณด๊ธฐ๋ฅผ ์ํ๋ ์๋งํผ ์์ฑ/๊ณต์ 
- ์ํธ๋ฅผ ์ฌ์ฉํ์ฌ ๊ณต์  ๋ณด๊ธฐ ์ก์ธ์ค ๋ณดํธ
- ํญ์ ์๋ก ์์ํ๋ ๋์  ๊ธฐ์กด ๋ณด๊ธฐ๋ฅผ ์ ๋ณด๊ธฐ์ ๊ธฐ๋ฐ์ผ๋ก ๋ณต์ฌ
- ํน์  ์์๋ฅผ *ํ์*๋ก ํ์
- ์์ ํ๋์ ๋ํ ์ถ๊ฐ ์ ๋ณด/์ง์นจ ์ถ๊ฐ
- ๋ฉ์ผ์ ํตํด ์์ ์ ์ถ ์๋ฐ์ดํธ๋ฅผ ๋ฐ๋๋ก ๊ตฌ์ฑ

### ์์ฑ, ์ฌ์ฉ์ ์ ์ ๋ฐ ๊ณต์  ๋ฐฉ๋ฒ
![Form](https://user-images.githubusercontent.com/86527202/138726122-85ff583c-4a62-464e-99b0-c6b24f23d037.gif)

- ํ NocoDB


