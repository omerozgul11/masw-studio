# MASW Studio

**Shear-wave velocity from surface waves, from field record to report, on your own computer.**
A QuakeLogic Inc. product.

MASW Studio is Windows software for **Multichannel Analysis of Surface Waves (MASW)**. Load
the SEG-2 shot records from your seismograph and MASW Studio takes you all the way to a
layered shear-wave velocity (Vs) profile, Vs30, a 2D Vs cross-section of the line and a
branded technical report. Everything runs offline on the computer; no cloud account is
needed, and your data never leaves your machine.

![MASW Studio 2D Vs section of a survey line](images/guide-section-2d.png)

**[Download the free 14-day trial](https://github.com/omerozgul11/masw-studio-releases/releases/latest)** ·
**[Buy a licence](#licensing-and-pricing)** · **[Brochure and user guide (PDF)](https://github.com/omerozgul11/masw-studio-releases/releases/latest)**

---

## Who it is for

Geotechnical and geophysical engineers, site-investigation contractors, seismic
site-classification consultants and universities who acquire active-source MASW data and
need defensible Vs profiles and reports without a complex toolchain.

## What you can do

### Import your field data in seconds
Open SEG-2 files straight from the seismograph (`.sg2`, `.seg2`, `.dat`), a whole line at a
time, or time-column CSV. Geometry is read from the file headers and checked with you before
any analysis. The original records are never modified.

![Import summary](images/guide-import-summary.png)

### Clean, inspect and interpret dispersion
Preview band-pass filters and mutes beside the original gather, then calculate F–V and F–K
dispersion images. Trace the fundamental mode with a click, with acquisition-quality guides
that show where the array can and cannot resolve.

![Dispersion image with picked fundamental mode](images/guide-dispersion-picks.png)

### Invert to a layered Vs profile and Vs30
Forward-model Rayleigh and Love modes and run a bounded inversion that fits your picks. The
profile shows the Vs30 average line, with Vs30 reported only within your declared
interpretation depth.

![Velocity profile and model fit](images/guide-model-profile.png)

### See the whole line as a 2D section, and find voids
Every shot along a roll-along line becomes a station in a distance × depth Vs cross-section.
It uses a fine grid and smooth interpolation that never invents velocities beyond the
measured stations. The **void finder** view highlights slower ground (possible voids, loose
fill or soft zones) in red. Areas below the investigation depth are hatched, so nothing is
over-interpreted.

![Void finder](images/guide-section-void-finder.png)

### Professional reports, previewed before you save
Generate a QuakeLogic-branded technical PDF with survey details, site photos, processing
history, figures, models, Vs30, refraction QC and the 2D section. Page through it in the app
before saving. Figures export as PNG, SVG or PDF and tables as CSV.

![Report preview](images/guide-report-preview.png)

### Every past analysis in one Library
Search all your past projects by client, site, location or notes. Reopen any analysis where
you left off, or pull shots from earlier surveys into a new project, for example to combine
lines recorded on different days into one section.

![Library](images/guide-library.png)

### Learn it in ten minutes
A guided tour highlights each control and moves on as you work, using a bundled example
recording. The built-in user guide has screenshots of every step, and example SEG-2 data is
included.

![Guided tour](images/guide-tour-step.png)

## Technical summary

| | |
| --- | --- |
| Platform | Windows 10 (1809 or later) and Windows 11, 64-bit. About 1 GB of disk; 8 GB RAM recommended |
| Data | SEG-2 revision 1 (16/32-bit integer, 32/64-bit float), time-column CSV; up to 512 channels per shot |
| Processing | Detrend, zero-phase Butterworth filters, time and linear mutes, trace editing, stacking and splitting |
| Dispersion | Phase-shift F–V and F–K transforms with aperture and spatial-aliasing QC |
| Modelling | Rayleigh (P–SV) and Love (SH) modes, layered elastic earth, bounded least-squares inversion |
| Outputs | Vs profiles, Vs30, 2D Vs sections, refraction first-arrival QC, PDF reports, PNG/SVG/PDF/CSV exports |
| Projects | Self-contained `.qlmasw` files with automatic local recovery and undo/redo |
| Privacy | Fully offline. No account, no telemetry; licences are activated offline |

## Licensing and pricing

- **Free 14-day trial** with every feature. Results made during the trial are marked
  *TRIAL*.
- **Perpetual licence per computer.** It includes one year of updates and support; renew
  maintenance to keep receiving new versions. Versions released during your maintenance
  period remain yours permanently.
- **Multi-seat, academic and volume pricing** is available.
- Your projects always remain accessible: without a licence they can still be opened,
  viewed and saved.

**Pricing and quotes:** [sales@quakelogic.net](mailto:sales@quakelogic.net?subject=MASW%20Studio%20licence) ·
+1 (916) 899-0391 · [products.quakelogic.net](https://products.quakelogic.net/)

### How to buy and activate

1. Install the trial and open **License** in the left menu (or **Help → License**).
2. Copy the computer's **Machine ID** and send it to sales@quakelogic.net with your company
   name and the number of computers, or use **Request a licence** in the app.
3. You receive a licence file (`.qlicense`). Choose **Import licence file**. Activation
   is offline and instant.

To move a licence to a new computer, email us both Machine IDs.

## Support

[support@quakelogic.net](mailto:support@quakelogic.net). Email response within 3 business
days. Please include the MASW Studio version (shown in About) and what you were doing.

## Documentation

- **Brochure and user guide (PDF):** attached to each [release](https://github.com/omerozgul11/masw-studio-releases/releases/latest),
  and available in the app under User guide → Download PDF guide.
- The complete user guide, scientific methods and validation record are built into the app
  and work offline.

## Scientific basis and limitations

MASW Studio implements published methods (Park, Miller & Xia 1999; Xia, Miller & Park 1999;
Dunkin 1965; Haskell 1953), with forward modelling by the open-source disba solver. Models
are 1D, isotropic and layered. The 2D section is a pseudo-2D display of 1D models, not a 2D
inversion. Geophysical interpretation, including possible voids, requires qualified
professional judgement and independent confirmation.

## Legal

- [End-user licence agreement](EULA.md)
- [Third-party and open-source notices](THIRD-PARTY-NOTICES.md). The Qt/PySide source
  archives required by the LGPL are attached to each release.

© QuakeLogic Inc. All rights reserved. MASW Studio is commercial software; this repository
distributes the Windows installer and documentation only.
