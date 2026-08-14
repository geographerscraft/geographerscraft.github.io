# 📋 The Geographer's Craft — Categorized Broken Links & Action Plan

This catalog categorizes every non-working or legacy link across the 282 documents into four actionable groups:

1. **[Category 1] Internal Missing Files to Restore/Rehost Directly** (Files originally in Geographer's Craft).
2. **[Category 2] Legacy Hardcoded University Links to Geographer's Craft** (Old absolute UT/CU URLs to convert to `https://geographerscraft.github.io/...`).
3. **[Category 3] External University & Organization Links with Verified Modern URLs**.
4. **[Category 4] Historical Protocols (Gopher / 1990s FTP / Telnet)** with No Modern Replacement (Preserve as era artifacts).

---

## 1. Internal Missing Files to Restore or Rehost Directly (41 Files)

These files were originally created for *The Geographer's Craft* and can be repaired directly inside the repository:

| Original File / Target Path | Instances | Found in Pages | Proposed Direct Solution |
| :--- | :---: | :--- | :--- |
| `notes/gps/gps_ftoc.html` | 37 | `notes/gps/gps.html` | **Restore from `notes/gps/gps_ftoc.offline`** (Instantly fixes 37 links) |
| `notes/sources/sources_ftoc.html` | 1 | `notes/sources/sources_stoc.html` | **Restore from `notes/sources/sources_ftoc.offline`** |
| `notes/remote/gif/contents.html` (12 images) | 12 | `notes/remote/gif/contents.html` | **Fix redundant `gif/` subfolder path** in `src` attributes |
| `warmup/treasure/xkey.html` | 1 | `warmup/treasure/treasure.html` | **Relink to `warmup/treasure/key.html`** (solution key) |
| `students/archives/94-95/9495student.html` | 1 | `students/students.html` | Check Wayback Machine archive for 1994–1995 student project index |
| `students/archives/95-96/9596student.html` | 1 | `students/students.html` | Check Wayback Machine archive for 1995–1996 student project index |
| `students/archives/96-97/9697student.html` | 1 | `students/students.html` | Check Wayback Machine archive for 1996–1997 student project index |
| `students/archives/97-98/9798student.html` | 1 | `students/students.html` | Check Wayback Machine archive for 1997–1998 student project index |
| `students/archives/99-00/9900student.html` | 1 | `students/students.html` | Check Wayback Machine archive for 1999–2000 student project index |
| `rules/labrules.html` | 1 | `geninfo/geninfo.html` | Restore syllabus lab rules page from archive |
| `warmup/aquifer/aquifer_toc.html` | 1 | `warmup/aquifer/aqintro.html` | Restore Barton Springs aquifer lab TOC |
| `warmup/barriers/download/mainmap.gif` | 1 | `warmup/barriers/download/campushomepage2.html` | Restore UT Austin campus barriers map asset |

---

## 2. Legacy Hardcoded University Links to Geographer's Craft Pages

These links point to *The Geographer's Craft* pages using defunct 1990s UT Austin or CU Boulder absolute URLs. They should be updated to point directly to our live GitHub Pages site:

| Legacy Absolute University Link | Occurrences | Link Anchor Text | Proposed Live GitHub Pages URL |
| :--- | :---: | :--- | :--- |
| `http://www.utexas.edu/depts/grg/gcraft/notes/notes.html` | 6 | "lecture and discussion notes" | `https://geographerscraft.github.io/notes/notes.html` |
| `http://www.utexas.edu/depts/grg/gcraft/warmup/contents.html` | 6 | "warmup exercises and assignments" | `https://geographerscraft.github.io/warmup/warmup.html` |
| `http://www.utexas.edu/depts/grg/gcraft/notes/gps/gps.html` | 4 | "GPS Overview" | `https://geographerscraft.github.io/notes/gps/gps.html` |
| `http://www.utexas.edu/depts/grg/gcraft/notes/ethics/ethics.html` | 4 | "Ethical Issues in Electronic Info Systems" | `https://geographerscraft.github.io/notes/ethics/ethics.html` |
| `http://www.utexas.edu/depts/grg/gcraft/notes/cartocom/toc.html` | 4 | "Cartographic Communication" | `https://geographerscraft.github.io/notes/cartocom/cartocom.html` |
| `http://www.utexas.edu/depts/grg/gcraft/notes/sources/sources.html` | 4 | "Data Sources for GIS" | `https://geographerscraft.github.io/notes/sources/sources.html` |
| `http://www.utexas.edu/depts/grg/gcraft/exam/exam.html` | 4 | "study and review questions" | `https://geographerscraft.github.io/exam/exam.html` |
| `http://www.utexas.edu/depts/grg/gcraft/warmup/village/village.html` | 4 | "Your Village" | `https://geographerscraft.github.io/warmup/village/village.html` |
| `http://www.utexas.edu/depts/grg/gcraft/warmup/greytown/greytown.html` | 4 | "Greytown" | `https://geographerscraft.github.io/warmup/greytown/greytown.html` |
| `http://www.utexas.edu/depts/grg/gcraft/warmup/aerobics/aerobics.html` | 3 | "Digital Aerobics" | `https://geographerscraft.github.io/warmup/aerobics/aerobics.html` |
| `http://www.utexas.edu/depts/grg/gcraft/warmup/webserch/webserch.html` | 3 | "Web Search" | `https://geographerscraft.github.io/warmup/webserch/webserch.html` |
| `http://www.utexas.edu/depts/grg/gcraft/warmup/balcones/balcones.html` | 3 | "Balcones Canyonlands Habitat" | `https://geographerscraft.github.io/warmup/balcones/balcones.html` |
| `http://www.utexas.edu/depts/grg/gcraft/notes/coordsys/coordsys.html` | 2 | "Coordinate Systems Overview" | `https://geographerscraft.github.io/notes/coordsys/coordsys.html` |
| `http://www.utexas.edu/depts/grg/gcraft/notes/mapproj/mapproj.html` | 2 | "Map Projections Overview" | `https://geographerscraft.github.io/notes/mapproj/mapproj.html` |
| `http://www.utexas.edu/depts/grg/gcraft/notes/manerror/manerror.html` | 2 | "Managing Error" | `https://geographerscraft.github.io/notes/manerror/manerror.html` |
| `http://www.utexas.edu/depts/grg/gcraft/notes/legal/legal.html` | 2 | "Legal Issues Relating to GIS" | `https://geographerscraft.github.io/notes/legal/legal.html` |
| `http://www.utexas.edu/depts/grg/gcraft/notes/lifecycle/lifecycl.html` | 2 | "Project Lifecycle and Project Planning" | `https://geographerscraft.github.io/notes/lifecycle/lifecycl.html` |
| `http://www.utexas.edu/depts/grg/gcraft/projects/spring96/spring96.html` | 2 | "final projects prepared by class" | `https://geographerscraft.github.io/projects/spring96/spring96.html` |
| `http://www.Colorado.EDU/geography/gcraft/gif/menu.map` | 2 | Sidebar Image Map | `https://geographerscraft.github.io/gif/menu1.gif` |

---

## 3. External University & Organization Links (With Verified Modern URLs)

These are external institutional and project websites with verified, active modern replacements:

| Legacy URL | Link Text / Context | Verified Modern Replacement URL |
| :--- | :--- | :--- |
| `http://www.Colorado.EDU/geography/` | UC Geography Homepage | `https://www.colorado.edu/geography/` |
| `http://www.colorado.edu/` | University of Colorado Boulder | `https://www.colorado.edu/` |
| `http://www.utexas.edu/` | University of Texas at Austin | `https://www.utexas.edu/` |
| `http://www.utexas.edu/depts/grg/` | UT Austin Department of Geography | `https://liberalarts.utexas.edu/geography/` |
| `http://www.utexas.edu/depts/grg/main.html` | Geography Home Page | `https://liberalarts.utexas.edu/geography/` |
| `http://www.uconn.edu/` | University of Connecticut | `https://uconn.edu/` |
| `http://www.pdana.com/` | Peter H. Dana Personal Website | `https://www.pdana.com/` |
| `http://www.tenlinks.com` | Top Ten Internet Award (2000-2001) | `https://www.tenlinks.com/` |
| `http://www.utexas.edu/depts/grg/virtdept/contents.html` | The Virtual Geography Department Project | `https://web.archive.org/web/20050305001201/http://www.colorado.edu/geography/virtdept/contents.html` |
| `http://www.colorado.edu/geography/virtdept/resources/contents.htm` | Virtual Dept Internet Resources | `https://web.archive.org/web/20050305001201/http://www.colorado.edu/geography/virtdept/contents.html` |
| `http://www.links2go.com/topic/Geography` | Links2Go Award Badge | `https://web.archive.org/web/20000815053123/http://www.links2go.com/topic/Geography` |

---

## 4. Historical Era Links (Gopher / Anonymous FTP / BBS) — No Modern Suggestion

These links are **authentic historical artifacts of the 1994–1996 early internet**. They should be preserved as-is without replacement:

| Historical URL | Early Internet Protocol | Original Lab Context | Notes |
| :--- | :--- | :--- | :--- |
| `gopher://wiretap.spies.com/11/Gov/World` | Gopher | 1994 Internet Treasure Hunt | Famous 1990s Wiretap public text server |
| `gopher://wiretap.spies.com/00/Library/Classic/inaug.txt` | Gopher | 1994 Internet Treasure Hunt | Historic presidential speeches text |
| `gopher://wiretap.spies.com/00/Library/Classic/chicago.txt` | Gopher | 1994 Internet Treasure Hunt | Chicago manual text |
| `gopher://una.hh.lib.umich.edu/00/ebb/foreign/exrates.txt` | Gopher | Foreign Exchange Rates Exercise | Univ of Michigan Gopher bulletin board |
| `gopher://nebula.lib.vt.edu/00/bookshelf/ebooks/...` | Gopher | Gutenberg E-Books Exercise | Virginia Tech early text repository |
| `gopher://joeboy.micro.umn.edu/11/Ebooks/By%20Title/shake` | Gopher | Shakespeare E-Books Exercise | Univ of Minnesota (Birthplace of Gopher) |
| `gopher://tamuts.tamu.edu/11/.dir/` | Gopher | Texas Spatial Data Search | Texas A&M early spatial dataset server |
| `gopher://odie.miaid.nih.gov/11/aids` | Gopher | Public Health Data Search | NIH early Gopher directory |
| `gopher://ftp.cc.utexas.edu:3003/1/microlib/info/texan` | Gopher | Daily Texan Campus Newspaper | UT Austin Computation Center Gopher |
| `gopher://hoshi.cic.sfu.ca/11/dlam/cia` | Gopher | World Factbook Exercise | Simon Fraser University Gopher |
| `file://tnris.twdb.texas.gov/pub` | Anonymous FTP | Satellite & GIS Data Download | Texas Natural Resources Information System |
| `file://134.125.90.200/pub/tnris/remotesensing/austin.gif` | Raw IP FTP | Remote Sensing Imagery Download | 1990s raw IP address FTP transfer |
