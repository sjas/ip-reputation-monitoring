# Changelog

## 1.1.3 (2016-07-11)
- [Fix] Only the first spamhaus entry was updated and switched inactive.
- [Fix] Empty variable in `reputation-rbl.sh`
- [Fix] Add more logs in the Spamhaus monitor job.

## 1.1.2 (2016-03-03)
- [Feat] `AS_NUMBER` is not mandatory anymore. If not provided, CleanTalk won't
be retrieved.
- [Fix] SNDS reports are now properly retrieved.
- [Fix] Spamhaus reports are now properly parsed.

## 1.1.1 (2016-03-01)
- [Fix] API - Querying reputation source details returns an empty array. (#3)
- [Fix] Unit tests issue with Nose. (#5)

## 1.1.0 (2016-02-18)
- SNDS key is not mandatory anymore (thanks to @vmalguy)
- Base64 emails are now decoded when calling API
- Setting up Travis

## 1.0.0 (2016-02-08)
- Publishing sources on GitHub.
