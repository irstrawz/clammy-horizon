# Clammy
FFXI addon for AshitaXI v4 that displays basic clamming information. Bucket size & weight, countdown timer, and contents.

![](https://private-user-images.githubusercontent.com/14827266/483887124-d3ecca24-e92a-4062-abc9-d0e5403b32db.png?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NTY1NjYzNjcsIm5iZiI6MTc1NjU2NjA2NywicGF0aCI6Ii8xNDgyNzI2Ni80ODM4ODcxMjQtZDNlY2NhMjQtZTkyYS00MDYyLWFiYzktZDBlNTQwM2IzMmRiLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNTA4MzAlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjUwODMwVDE1MDEwN1omWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTg5NzA4N2EzZjU3N2Y5NGZjZTJiZmJlOThhMzE0MDEzZDg4OWZhNmNiOWQyN2E0MzVmNDc5MGUyNmE1NzRjZmQmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0In0.cmbO7OoCDFJ9lI2kyIdXzQOM2PPKl2T_lO3Lbdk9JFg)


![](https://private-user-images.githubusercontent.com/14827266/483887150-0a3e3602-dc3e-45ba-b08a-aa126d359e88.png?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NTY1NjYzNjcsIm5iZiI6MTc1NjU2NjA2NywicGF0aCI6Ii8xNDgyNzI2Ni80ODM4ODcxNTAtMGEzZTM2MDItZGMzZS00NWJhLWIwOGEtYWExMjZkMzU5ZTg4LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNTA4MzAlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjUwODMwVDE1MDEwN1omWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPWE3NDIyMWE3NjRkMWNhOWYzYzM2MjI2OTk0NGFiOTVjNTExNGViYzU0Yjg1ZGY3MTU4MTc4YjQ0Mzc1ZjEwYWUmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0In0.AFr75OUnJx4ysD_Dhed0ges_FXHumKIDQPqEl3JaznQ).
![](https://private-user-images.githubusercontent.com/14827266/483887187-00f2161b-c8a1-469d-9294-930df5379f12.png?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NTY1NjYzNjcsIm5iZiI6MTc1NjU2NjA2NywicGF0aCI6Ii8xNDgyNzI2Ni80ODM4ODcxODctMDBmMjE2MWItYzhhMS00NjlkLTkyOTQtOTMwZGY1Mzc5ZjEyLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNTA4MzAlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjUwODMwVDE1MDEwN1omWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPWU5NGUyNGFjM2E5ZjE2YzAwZTQyMThmOTI1MDk3ZmE3NzgxYTA0YjEwYmYxODRhYzJhNjlhZWUyNjc2Y2FhN2MmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0In0.Nncmr1jh_xZAfF0zuO0UqvoNP10oqbyRfzewK5069Ts)

### Cleaning up old config
If you are updating this from the previous version of Clammy, please make sure to delete your old config file at:

`%gameinstalldirectory%\Game\config\addons\Clammy\%charactername%_######\settings.lua`

## Commands:
### Options
 `/clammy` *Opens a config menu for general configs*
 `/clammy showvalue [true/false/...]` *Turn display of estimated value on/off*  
 `/clammy showitems [true/false/...]` *Turn display of individual items on/off*  
 `/clammy log [true/false/...]` *Turns on/off results logging - stores file in /addons/Clammy/logs*
 `/clammy tone [true/false/...]` *Turns on/off playing a tone when clamming point is ready to dig*  
 `/clammy logbrokenbucketitems [true/false/...]` *Turns on/off logging if the bucket breaks*
 `/clammy showsessioninfo [true/false/...]` *Turns on/off showing gil/hr, buckets purchased, and total gil earned*
 `/clammy usebucketvalueforweightcolor [true/false/...]` *turns on/off current weight value turning red at certain gil amounts*
 `/clammy setweightvalues [highvalue/midvalue/lowvalue] #####` *Specify a value for when bucket color should turn red*
 `/clammy resetsession` *Resets the current clamming time, buckets purchased, items in bucket, gil/hr, and total gil earned*

### Debug
 `/clammy reset` *Manually clear bucket information*
 `/clammy weight` *Manually adjust bucket weight*

---

## Fork notes (Ashita 4.3)

This copy carries local fixes for Ashita 4.3. Upstream has not been updated
since October 2025 and does not load on 4.3 as-is.

**ImGui 4.3 compatibility.** `imgui.SetWindowFontScale` was removed in the
ImGui version bundled with Ashita 4.30. All four call sites in `renderClammy`
now use `PushFont`/`PopFont` with a captured base font size, with a balancing
`PopFont` before `imgui.End`.

**Key item detection.** Ashita 4.30 rebuilt the key item pointer for the
current retail client, so `GetPlayer():HasKeyItem()` returns false for every
id on the HorizonXI client build — verified by scanning ids 0-2047 and finding
none set. Bucket possession is now tracked from chat text instead, via a
`hasClammingKit` helper that still tries the real API first and latches onto
it permanently if it ever starts working again.

**Bucket break handling.** Break detection previously lived inside the
"You find a ..." item-matching loop, so it only fired when the break arrived
alongside a dig message. Overweight breaks took that path and froze the
display; creature breaks did not and reset correctly. Detection is now
standalone and deferred one frame, so it runs after the dig's item has been
added regardless of message order, then clears the bucket and logs it as
lost rather than turned in.

**Stuck broken flag.** `bucketIsBroke` was never cleared when a bucket was
emptied, leaving `hasBucket=false` plus `bucketIsBroke=true` — a state that
matches no branch in `handleBucket` and pinned bucket health at 0% until the
next dig.

**Missed turn-ins.** Obtaining a kit while a bucket is still held now closes
the old one out as a turn-in, so running from the NPC before the text renders
no longer carries contents into the new bucket.

**Bucket health at multiples of 50.** The health bar tracks the final 50
ponzes and used `relativeWeight > 50`, so at exactly 50 remaining it fell
through to `50 % 50 == 0` and displayed an empty bucket. Every capacity
upgrade lands precisely on that boundary. Changed to `>=`.

**Removed the gil earnings block** from the UI. The underlying values are
still calculated because the CSV logger writes them per bucket.
