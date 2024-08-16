## Project Islam

### 1. Milestone

1. Data collection and authenticity
   - Quran
   - saha sita
2. Translation in Urdu and English
3. Create APIs

### Features

- Data collection and authenticity

  - Quran
  - Saha sita

- Give unique content identifier

  - Quran
  - Books
  - Hadith
  - Ayah

- Web pages for Quran and Hadith

- Simple search with words

- Collect other Hadith books

- Collect serah books

- Collect Fatawas

- Collect audio tilawat, leactures etc

- Collect Video content (e.g Youtube videos)

- NLP

  - Range ayahs
  - Understand book related to user query
  - Find in operate book (Useful for AI search)

- Quran

  - Tag each Ayah
  - Attach context
  - Link same Topics (e.g Hazrat Mosa (A.S) Story separated in Quran, link them )
  - Attach Hadithes to Ayah (e.g Zakat related Hadith attach them to Ayah)
  - Tafaseer
  - Audio Tilawat
  - Detailed information about each Ayah Word (e.g root, Subject, Object or verb and in context meaning etc)

- Question and Answers

- Portal for Islamic Madaras

  - Create website for each madrasa
  - Get data from each Madrasa (e.g Passes Aulma etc)
  - Allow each madarsa to upload Fatwa
  - End users can subscribe to any madrasa (notify when new Fatwa upload or any Alam passed etc)
  - Stamp of Madrasa and Stamp of Mufti in Fatwa

- Mufti Portal (Degree holder only)

  - Can upload Fatwa
  - End users can subscribe
  - Mufti Stamp on Fatwa
  - Mufti can create Private notes
    - Shareable notes to specific person or publicly

- Digitalize data

- Translate data

- Voice search

  - translate voice into english perform search and get data in specific language
  - Default language is used to translate voice

- End user can specify default language

- Auto correct user query (e.g Did you mean)

- AI Search

  - Convert data into vector embedding
    - Store on database (e.g Postgres with PgVector)
  - Create query embedding
    - Convert query into hash
    - Save hash into database (to avoid create duplicate embedding for same query)

- Project Islam SDK
  - Read Access to all APIs
  - APIs with types
  - Audio files (e.g Tilawat, Lectures etc)
  - Offline support for APIs and Audio (Save data once downloaded - Mobile app)
  - Pre download support (Specify which data is used on installation - Mobile app)
