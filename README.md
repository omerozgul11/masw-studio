<p align="center">
  <img src="images/quakelogic-q-logo.png" width="96" alt="QuakeLogic">
</p>

<h1 align="center">QuakeLogic MASW Studio</h1>

<p align="center"><strong>Standalone, offline MASW analysis: from multichannel field records to shear-wave velocity profiles, Vs30, 2D sections and reports.</strong><br>
No account. No internet connection. Everything runs on your own computer.</p>

<p align="center">
  <a href="https://github.com/omerozgul11/masw-studio-releases/releases/download/v1.3.0/MASW-Studio-Setup-1.3.0.exe"><strong>⬇ Download for Windows (installer, v1.3.0)</strong></a> ·
  <a href="https://github.com/omerozgul11/masw-studio-releases/releases/download/v1.3.0/MASW-Studio-Brochure-and-User-Guide.pdf">brochure &amp; user guide (PDF)</a> ·
  <a href="marketing/QuakeLogic-MASW-Studio-Datasheet.pdf"><strong>product datasheet (PDF)</strong></a> ·
  <a href="https://github.com/omerozgul11/masw-studio-releases/releases">all releases</a> ·
  <a href="#licensing">buy a licence</a>
</p>

---

## What it is

QuakeLogic MASW Studio is a Windows desktop application for **Multichannel Analysis of Surface
Waves (MASW)**. It takes you from the shot records of an active-source survey (SEG-2, SEG-Y, DoReMi .drm or text) to a defensible,
fully documented result:
- import and geometry review, then transparent, non-destructive preprocessing
- F–V and F–K dispersion images, with picking of named modes
- Rayleigh and Love forward modelling and bounded inversion to a layered Vs profile and Vs30
- a **2D Vs section of the whole line with a void finder**, plus refraction QC
- a professional PDF report you can preview before saving

A Library keeps every past analysis ready to reopen or combine.

It is built for geotechnical and geophysical engineers who need results they can explain. Raw
records are never modified, every processing step and parameter is recorded, interpretation depth
must be declared before Vs30 is reported, and the software never presents a non-unique layered
model or a pseudo-2D section as more than it is.

<p align="center"><img src="images/guide-section-2d.png" width="900" alt="2D Vs section of a survey line"></p>

## Highlights

| | |
|---|---|
| **Truly standalone** | One installer, one icon, its own application window, bundled runtime. No services, no ports, no cloud. Works on a laptop in the field. |
| **Field data in seconds** | SEG-2 (`.sg2`, `.seg2`, `.dat`, including 20-bit), SEG-Y (`.sgy`, `.segy`), DoReMi `.drm` and time-column text (`.csv`, `.txt`, `.dat`), a whole line at once. The format is recognised from the file contents. Geometry is read from the headers and confirmed before analysis. |
| **Transparent processing** | Detrend, zero-phase Butterworth filters and time/linear mutes, previewed beside the original record. Trace editing, stacking and splitting are reversible and audited. |
| **Dispersion you can trust** | Phase-shift F–V and F–K transforms with aperture and spatial-aliasing QC guides. Click-to-pick named modes with explicit uncertainty. |
| **Modelling and inversion** | Rayleigh (P–SV) and Love (SH) modes of a layered elastic earth. Bounded least-squares inversion with convergence history. A Vs30 average line over 0–30 m. |
| **2D section and void finder** | Every station of a roll-along line, interpolated on a fine grid without overshoot. The void-finder view shows slower ground in red, investigation depth is hatched, and velocity inversions are flagged. |
| **Reports and exports** | A branded technical PDF with a page-by-page preview. PNG/SVG/PDF figures and CSV tables. |
| **Library of past analyses** | Search every project by client, site or notes, reopen it where you left off, or pull its shots into a new project. |
| **Learn it in ten minutes** | A guided tour with a bundled example SEG-2 file, plus an illustrated user guide built in. |
| **Your data stays yours** | Fully offline, no telemetry, local recovery and undo/redo, and self-contained `.qlmasw` projects. |

## Product datasheet

An 8-page datasheet for engineers, procurement and project managers covers the
workflow, standard features, supported field data, system requirements, licensing
options and full technical specifications. Download it to print or share:
**[QuakeLogic MASW Studio datasheet (PDF)](marketing/QuakeLogic-MASW-Studio-Datasheet.pdf)**.

<p align="center"><a href="marketing/QuakeLogic-MASW-Studio-Datasheet.pdf"><img src="marketing/datasheet-preview-1.png" width="900" alt="Datasheet: cover, overview and key features"></a></p>
<p align="center"><a href="marketing/QuakeLogic-MASW-Studio-Datasheet.pdf"><img src="marketing/datasheet-preview-2.png" width="900" alt="Datasheet: supported data, technical specifications and contacts"></a></p>

## A tour of the application

### 1. Start and the guided tour
The first launch opens a step-by-step tour. It highlights each control, explains it in plain
language and moves on as you work, using a bundled example SEG-2 recording.

<p align="center"><img src="images/guide-tour-step.png" width="900" alt="Guided tour"></p>

### 2. Import and geometry
Open SEG-2, SEG-Y, DAT, DoReMi .drm or CSV shot records. The import summary shows channels, sampling and the source and
receiver positions read from the file, and the geometry is confirmed before any analysis.

<p align="center"><img src="images/guide-import-summary.png" width="900" alt="Import summary"></p>
<p align="center"><img src="images/guide-dataset-gather.png" width="900" alt="Shot gather and geometry"></p>

### 3. Preprocessing
Preview filters, detrending and mutes beside the original record, then apply the exact previewed
sequence. Raw data are never modified, and every step can be removed.

<p align="center"><img src="images/guide-preprocessing-preview.png" width="900" alt="Preprocessing preview"></p>

### 4. Dispersion and picking
Calculate F–V and F–K images, then trace the fundamental mode with a click. Acquisition-QC guides
show where the array can and cannot resolve.

<p align="center"><img src="images/guide-dispersion-picks.png" width="900" alt="Dispersion image with picks"></p>

### 5. Model, inversion and Vs30
Forward-model Rayleigh or Love modes, run the bounded inversion and review the fit. The profile
shows the Vs30 average line.

<p align="center"><img src="images/guide-model-profile.png" width="900" alt="Velocity profile and model fit"></p>

### 6. 2D Vs section and void finder
Shots along a line become a distance × depth cross-section with labelled contours. The void finder
highlights slower ground, a possible void, loose fill or soft zone, in red.

<p align="center"><img src="images/guide-section-2d.png" width="900" alt="2D Vs section"></p>
<p align="center"><img src="images/guide-section-void-finder.png" width="900" alt="Void finder"></p>

### 7. Report
Enter survey details and photos, preview the technical PDF page by page, and save it.

<p align="center"><img src="images/guide-report-preview.png" width="900" alt="Report preview"></p>

### 8. Library
Every analysis on the computer, searchable. Open one to continue, or add its shots to the current
project.

<p align="center"><img src="images/guide-library.png" width="900" alt="Library of past analyses"></p>

## Licensing

MASW Studio runs as a full **14-day trial** from first use on a computer. During the trial every
figure, table, section and report is marked **TRIAL**. Afterwards, projects can still be opened,
viewed and saved, but new calculations and exports need a licence.

A licence is a small signed `.qlicense` file issued by QuakeLogic for the **Machine ID** shown on
the **License** page. Import it there: it is verified offline and never needs a connection.
Licences are perpetual for the versions they cover and include updates released until their
maintenance date (one year, renewable). Multi-seat, academic and volume pricing is available.
Request a quote at <sales@quakelogic.net> or +1 (916) 899-0391. See the
[licence agreement](EULA.md).

<p align="center"><img src="images/guide-license.png" width="900" alt="License page"></p>

## Download and install

**Windows 10 (1809 or later) / 11, 64-bit.** About 1 GB of disk; 8 GB RAM recommended.

1. Download the installer: [MASW-Studio-Setup-1.3.0.exe](https://github.com/omerozgul11/masw-studio-releases/releases/download/v1.3.0/MASW-Studio-Setup-1.3.0.exe)
   (numbered versions and checksums are on the [Releases](https://github.com/omerozgul11/masw-studio-releases/releases) page).
2. Run it, accept the licence agreement and leave **Launch MASW Studio** selected. Installing
   for all users asks for administrator approval.
3. Later, start it from the Start menu, the desktop icon or by double-clicking a `.qlmasw` project.
   It opens in its own window, and closing the window stops it.

Upgrading keeps all projects, recovery copies and preferences. The installer is not yet code-signed,
so Windows may show **Unknown publisher**: choose **More info → Run anyway**.

## Supported data

| Input | Notes |
|---|---|
| SEG-2 revision 1 | `.sg2`, `.seg2`, `.seg`, `.dat`; encodings 1, 2, 3, 4, 5 (16/32-bit integer, 20-bit packed, 32/64-bit IEEE float); up to 512 channels, 256 MiB per file; geometry and units from the headers |
| SEG-Y rev 0/1/2 | `.sgy`, `.segy`, `.dat`; IBM or IEEE float, 8/16/32-bit integer; big- or little-endian; geometry from coordinates or offsets |
| DoReMi (SARA) | `.drm` recordings; if one uses a layout this version cannot read, export it as SEG-2 from the DoReMi or GeoExplorer |
| Text columns | `.csv`, `.txt`, `.dat`, `.asc`; a time column (s or ms) plus one column per channel; comma, semicolon, tab or space separated; header optional |
| `.qlmasw` projects | self-contained projects with raw data, processing, picks, models, notes and photos |
| Not supported | SU, SEG-D and other proprietary formats; export SEG-2 or SEG-Y instead |

## Scientific method in one paragraph

Each enabled trace is processed exactly as recorded in the project. F–V images use the phase-shift
transform (Park, Miller &amp; Xia 1999) with phase-coherence or energy normalisation, and F–K images
use the spatial Fourier transform. Aperture and spatial-aliasing limits are drawn as QC guides.
Theoretical dispersion curves of the layered elastic model come from the open-source disba solver
(Dunkin compound matrix for Rayleigh, Thomson–Haskell for Love). Inversion is a bounded,
uncertainty-weighted trust-region least-squares fit with fixed Vp and density (Xia, Miller &amp; Park
1999). Vs30 is the travel-time average over the top 30 m, reported only within the declared
interpretation depth. The 2D section places each station's 1D model at its spread midpoint and
interpolates with a shape-preserving curve. It is a pseudo-2D presentation, not a 2D inversion.
Full details and citations are in the scientific-methods document built into the app.

## Documentation

| Document | Content |
|---|---|
| [Brochure &amp; user guide (PDF)](https://github.com/omerozgul11/masw-studio-releases/releases/download/v1.3.0/MASW-Studio-Brochure-and-User-Guide.pdf) | product overview and the complete illustrated user guide (also in the app under *User guide*) |
| [Product datasheet (PDF)](marketing/QuakeLogic-MASW-Studio-Datasheet.pdf) | 8-page overview: features, supported data, requirements, licensing options, specifications |
| In-app user guide | installation, every workspace, the 2D section, Library, licensing, shortcuts |
| In-app scientific methods and validation record | algorithms, equations, citations and test evidence |
| [Licence agreement](EULA.md) | end-user licence agreement |
| [Third-party notices](THIRD-PARTY-NOTICES.md) | open-source components and their licences; Qt/PySide sources are attached to each release (LGPL) |

## Support

QuakeLogic Inc. · 2008 Opportunity Dr., Suite 130, Roseville, CA 95678, USA ·
+1 (916) 899-0391 · <sales@quakelogic.net> · <support@quakelogic.net> (response within 3 business days) ·
<https://www.quakelogic.net> · [MASW Studio on products.quakelogic.net](https://products.quakelogic.net/product/quakelogic-masw-studio-professional-masw-analysis-software/)

## Licence

MASW Studio is proprietary software licensed under the [end-user licence agreement](EULA.md). It
includes open-source components under their own licences ([third-party notices](THIRD-PARTY-NOTICES.md)).

---
<sub>© QuakeLogic Inc. This repository distributes the MASW Studio installer and documentation only; the source code is private.</sub>
