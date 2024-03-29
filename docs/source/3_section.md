# Description of WHOTS-17 Mooring

The WHOTS-17 mooring, deployed on August 26, 2021, from R/V Oscar Elton Settle,
was outfitted with two complete sets of Air-Sea Interaction Meteorological
([ASIMET](https://uop.whoi.edu/UOPinstruments/asimet/)) sensors on the buoy and underneath subsurface instruments from 7 to
155 m depth, and near the bottom. See {cite}`Santiago-Mandujano2022a,
Santiago-Mandujano2022b` for a complete description of the buoy.
The WHOTS-17 was recovered on July 25, 2022.

The buoy is equipped with meteorological instrumentation, including two
complete Air-Sea Interaction Meteorological
([ASIMET](https://uop.whoi.edu/UOPinstruments/asimet/)) systems on the buoy and
underneath subsurface instruments from 7 to 155 m depth and near the bottom.
The [buoy
tower](https://uop.whoi.edu/currentprojects/WHOTS/docs/whots17towertop.pdf)
contains standalone sensors: [Vaisala
WXT-520](http://vocab.nerc.ac.uk/collection/L22/current/TOOL0894/2/)
multi-variable (temperature, humidity, pressure, wind, and precipitation), an
[SBE-39
temperature](http://vocab.nerc.ac.uk/collection/L22/current/TOOL1122/1/) sensor
adapted to measure air temperature, and Lascar RH/ATMP. The ASIMET sensors
include air temperature and relative humidity
([ATMP/HRH](http://vocab.nerc.ac.uk/collection/L22/current/TOOL1605/1/)),
barometric pressure
([BPR](http://vocab.nerc.ac.uk/collection/L22/current/TOOL0708/1/)), wind speed
and direction
([WSPD](http://vocab.nerc.ac.uk/collection/L22/current/TOOL0260/))
and ([WDIR](http://vocab.nerc.ac.uk/collection/L22/current/TOOL0260/)),
precipitation
([PRC](http://vocab.nerc.ac.uk/collection/L22/current/TOOL0671/1/)), longwave
([LWR](http://vocab.nerc.ac.uk/collection/L22/current/TOOL0083/4/)) and
shortwave ([SWR](http://vocab.nerc.ac.uk/collection/L22/current/TOOL0666/1/))
radiations, and seas surface temperature (SST) and salinity (SSS). The buoy
tower also contains a radar reflector, two marine lanterns, and two Iridium
satellite transmission systems that provide continuous buoy position
monitoring. Two Rover and one Melo sensor from Xeos Melo Global Positioning
System (GPS) receiver recorded the buoy's positions. A fourth positioning
system (Xeos Kilo transmitter) was mounted beneath the hull. A [Battelle pCO2
system](http://vocab.nerc.ac.uk/collection/L22/current/TOOL0878/1/), a pumped
[SBE-16 CTD](http://vocab.nerc.ac.uk/collection/L22/current/TOOL0100/3/), and a
[SAMI-2 pH sensor](http://vocab.nerc.ac.uk/collection/L22/current/TOOL1613/1/)
were mounted to the buoy's underside. A Sea-Bird
[SBE-63](http://vocab.nerc.ac.uk/collection/L22/current/TOOL0739/1/) hosted a
dissolved oxygen sensor. A [Wetlabs ECOFLNTUS chlorophyll
fluorometer](http://vocab.nerc.ac.uk/collection/L22/current/TOOL1629/2/) was
also mounted on the buoy hull.

Five internally logging Sea-Bird SBE-56 temperature sensors were bolted to the
buoy hull's underside, measuring sea surface temperature (SST) and salinity.
The [SBE-56s](https://vocab.nerc.ac.uk/collection/L22/current/TOOL0687/1/) measured SST once every 60 sec between 80-110 cm below the surface.
Two SBE-37 MicroCATs were at 1.55m, measuring at every 300s (See {numref}`table-7`).

```{table} WHOTS-17 MicroCAT and SBE-56 Temperature Sensor Information.
:name: table-7
:widths: auto
:align: center

| **Instrument** | **SN** | **Depth (m)** | **Sample Interval (sec)** |
|:--------------:|:------:|:-------------:|:-------------------------:|
|     SBE-56     |  6150  |     0.80      |            60             |
|     SBE-56     |  6239  |     0.80      |            60             |
|     SBE-56     |  6410  |     0.95      |            60             |
|     SBE-56     |  6412  |     1.10      |            60             |
|     SBE-56     |  7211  |     0.80      |            60             |
|    MicroCAT    |  5996  |     1.55      |            300            |
|    MicroCAT    |  1727  |     1.55      |            300            |
```

Underwater instrumentation included 18 MicroCATs (SeaBird SBE-37) deployed to
record temperature and conductivity (C-T) at 7, 15, 25, 35, 40, 45, 50, 55, 65,
75, 85, 95, 105, 120, 135, 155, and two at about 40 m off the bottom. The
MicroCATs at 7, 45, 85, 105, 120, 135, 155, and the two near the bottom
included a pressure sensor. Two upward-looking RDI ADCPs were deployed at 47.5
m (600 kHz) and 125 m (300 kHz), respectively, and two Next Generation Vector
Measurement Current Meters (VMCMs) were deployed at 10 and 30 m, respectively,
to measure current speed and direction.

The {numref}`mooring_subsurface` provides a listing of the WHOTS-17 subsurface
instrumentation at their nominal depths on the mooring, along with serial
numbers, sampling rates, and other pertinent information. A cold water spike
was induced to the UH MicroCATs before deployment
({numref}`mooring_subsurface`) and after recovery {numref}`table-8` by placing
an ice pack in contact with their temperature sensor to check for any drift in
their internal clock. To produce a spike in the ADCP data, each instrument’s
transducer was rubbed gently by hand for 20 seconds ({numref}`table-9`
, and {numref}`table-10`).

```{table} WHOTS-17 mooring subsurface instrument deployment information. SN=Serial Number; I=Instrument; D=Depth(m); PSN=Pressure Serial Number; SI=Sample Interval(s); SL=Starting Logging ; CSB=Cold Spike Begin; CSE= Cold Spike End; TIW= Time in Water. All times are in UTC (mm/dd/yy hh:mm:ss). * VMCM Spin start times, ** AC=Acoustic Receiver ( Vemco VR2W Acoustic Receiver 69 kHz attached to 25 m MicroCAT loadbar).
:name: mooring_subsurface
:widths: auto
:align: center

| **SN** |    **I**    |     **D**      | **PSN** | **SI** |      **SL**      |       **CSB**       |      **CSE**       |     **TIW**      |
| :----: | :---------: | :------------: | :-----: | :----: | :--------------: | :-----------------: | :----------------: | :--------------: |
|  6892  |  MicroCAT   |       7        | 2651324 |   75   | 8/25/21 0:00:00  |   8/25/21 0:03:00   |  8/25/21 1:06:00   | 8/25/21 20:20:00 |
|   35   |    VMCM     |       10       |   N/A   |   60   |  8/7/21 2:01:00  | 08/25/21 19:08:00\* |        N/A         | 8/25/21 19:57:00 |
|  3382  |  MicroCAT   |       15       |   N/A   |  180   | 8/25/21 0:00:00  |   8/25/21 0:03:00   |  8/25/21 1:06:00   | 8/25/21 19:42:00 |
|  4663  |  MicroCAT   |       25       |   N/A   |  180   | 8/25/21 0:00:00  |   8/25/21 0:03:00   |  8/25/21 1:06:00   | 8/25/21 19:37:00 |
| 135934 |   AC \*\*   |       25       |   N/A   |  N/A   | 8/12/21 19:00:00 |         N/A         |        N/A         | 8/25/21 19:37:00 |
|   58   |    VMCM     |       30       |   N/A   |   60   |  8/7/21 2:40:00  | 8/25/21 19:22:00\*  |        N/A         | 8/25/21 19:32:00 |
|  3633  |  MicroCAT   |       35       |   N/A   |  180   | 8/25/21 0:00:00  |   8/25/21 0:03:00   |  8/25/21 1:06:00   | 8/25/21 19:24:00 |
|  3381  |  MicroCAT   |       40       |   N/A   |  180   | 8/25/21 0:00:00  |   8/25/21 0:03:00   |  8/25/21 1:06:00   | 8/25/21 19:20:00 |
|  3668  |  MicroCAT   |       45       |  5579   |  240   | 8/25/21 0:00:00  |   8/25/21 0:03:00   |  8/25/21 1:06:00   | 8/25/21 19:15:00 |
| 13917  | 600kHz ADCP |      47.5      |   N/A   |  600   | 8/25/21 5:50:00  |  {numref}`table-9`  | {numref}`table-10` | 8/25/21 20:39:00 |
|  3619  |  MicroCAT   |       50       |   N/A   |  180   | 8/25/21 0:00:00  |   8/25/21 0:03:00   |  8/25/21 1:06:00   | 8/25/21 20:41:00 |
|  3620  |  MicroCAT   |       55       |   N/A   |  180   | 8/25/21 0:00:00  |   8/25/21 0:03:00   |  8/25/21 1:06:00   | 8/25/21 20:41:00 |
|  3621  |  MicroCAT   |       65       |   N/A   |  180   | 8/25/21 0:00:00  |   8/25/21 0:03:00   |  8/25/21 1:06:00   | 8/25/21 20:44:00 |
|  3632  |  MicroCAT   |       75       |   N/A   |  180   | 8/25/21 0:00:00  |   8/25/21 0:03:00   |  8/25/21 1:06:00   | 8/25/21 20:46:00 |
|  4699  |  MicroCAT   |       85       |  10209  |  240   | 8/25/21 0:00:00  |   8/25/21 0:03:00   |  8/25/21 1:06:00   | 8/25/21 20:47:00 |
|  3791  |  MicroCAT   |       95       |   N/A   |  180   | 8/25/21 0:00:00  |   8/25/21 0:03:00   |  8/25/21 1:06:00   | 8/25/21 20:49:00 |
|  2769  |  MicroCAT   |      105       |  2949   |  240   | 8/25/21 0:00:00  |   8/25/21 0:03:00   |  8/25/21 1:06:00   | 8/25/21 20:52:00 |
|  4700  |  MicroCAT   |      120       | 2479944 |  240   | 8/25/21 0:00:00  |   8/25/21 0:03:00   |  8/25/21 1:06:00   | 8/25/21 21:00:00 |
|  7637  | 300kHz ADCP |      125       |   N/A   |  600   | 8/25/21 6:07:00  |  {numref}`table-9`  | {numref}`table-10` | 8/25/21 21:00:00 |
|  2451  |  MicroCAT   |      135       |  1556   |  240   | 8/25/21 0:00:00  |   8/25/21 0:03:00   |  8/25/21 1:06:00   | 8/25/21 21:01:00 |
|  4701  |  MicroCAT   |      155       |  10211  |  240   | 8/25/21 0:00:00  |   8/25/21 0:03:00   |  8/25/21 1:06:00   | 8/25/21 21:04:00 |
| 11380  |  MicroCAT   | 39m off Anchor | 2146835 |  300   | 8/25/21 0:00:00  |   8/25/21 0:03:00   |  8/25/21 1:06:00   | 8/26/21 0:36:00  |
| 11381  |  MicroCAT   | 39m off Anchor | 2146836 |  300   | 8/25/21 0:00:00  |   8/25/21 0:03:00   |  8/25/21 1:06:00   | 8/26/21 0:36:00  |
```

```{table} WHOTS-17 mooring C-T and ADCP Instruments recovery information. D=Depth(m); Sea-Bird 37 Serial Number (SN). TOW=Time out of water; TOS=Time of Spike; TOES=Time of End Spike; TLS=Time Logging Stopped; ITS=Instrument Time when Stopped; SL=Samples Logged; DQ=Data Quality; FN=File Name(all file names start with whots17_.).  All times are in UTC (mm/dd/yy hh:mm:ss).
:name: table-8
:widths: auto
:align: center

| **D**  |   **SN**   |    **TOW**    |    **TOS**    |   **TOES**    |    **TLS**    |    **ITS**    | **SL** |     **DQ**      |     **FN**      |
| :----: | :--------: | :-----------: | :-----------: | :-----------: | :-----------: | :-----------: | :----: | :-------------: | :-------------: |
|   7    |    6892    | 7/26/22 5:05  | 7/26/22 18:26 | 7/26/22 19:04 | 7/27/22 3:05  | 7/27/22 3:05  | 387221 | C failed-2/2022 |   7m_6892.XML   |
|   15   |    3382    | 7/26/22 5:09  | 7/26/22 18:26 | 7/26/22 19:04 | 7/27/22 3:11  | 7/27/22 3:11  | 161343 |      Good       |  15m_3382.asc   |
|   25   |    4663    | 7/26/22 5:09  | 7/26/22 18:26 | 7/26/22 19:04 | 7/27/22 2:58  | 7/27/22 2:58  | 161340 |      Good       |  25m_4663.XML   |
|   35   |    3633    | 7/26/22 3:57  | 7/26/22 18:26 | 7/26/22 19:04 | 7/27/22 2:52  | 7/27/22 2:51  | 161337 |      Good       |  35m_3633.XML   |
|   40   |    3381    | 7/26/22 3:54  | 7/26/22 18:26 | 7/26/22 19:04 | 7/27/22 5:47  | 7/27/22 5:47  | 161394 |      Good       |  40m_3381.asc   |
|   45   |    3668    | 7/26/22 3:49  | 7/26/22 18:26 | 7/26/22 19:04 | 7/27/22 2:41  | 7/27/22 2:39  | 121000 | P failed-1/2022 |  45m_3668.asc   |
|  47.5  | ADCP 13917 | 7/26/22 3:45  | 7/26/22 19:08 | 7/26/22 19:41 | 7/27/22 6:53  | 7/27/22 7:00  | 48391  |      Good       |     000.000     |
|   50   |    3619    | 7/26/22 3:44  | 7/26/22 18:26 | 7/26/22 19:04 | 7/27/22 2:47  | 7/27/22 2:46  | 161334 |      Good       |  50m_3619.asc   |
|   55   |    3620    | 7/26/22 3:43  | 7/26/22 18:26 | 7/26/22 19:04 | 7/27/22 6:10  | 7/27/22 6:10  | 161404 |      Good       |  55m_3620.asc   |
|   65   |    3621    | 7/26/22 3:42  | 7/26/22 18:26 | 7/26/22 19:04 | 7/27/22 3:38  | 7/27/22 3:38  | 161353 |      Good       |  60m_3621.asc   |
|   75   |    3632    | 7/26/22 3:41  | 7/26/22 18:26 | 7/26/22 19:04 | 7/27/22 6:06  | 7/27/22 6:05  | 161402 |      Good       |  75m_3632.asc   |
|   85   |    4699    | 7/26/22 3:39  | 7/26/22 18:26 | 7/26/22 19:04 | 7/27/22 6:01  | 7/27/22 6:01  | 121051 |      Good       |  85m_4699.XML   |
|   95   |    3791    | 7/26/22 3:38  | 7/26/22 18:26 | 7/26/22 19:04 | 7/27/22 5:56  | 7/27/22 5:56  | 161399 |      Good       |  95m_3791.asc   |
|  105   |    2769    | 7/26/22 3:37  | 7/26/22 18:26 | 7/26/22 19:04 | 7/27/22 3:32  | 7/27/22 3:33  | 65459  | Failed-11/2021  |  105m_2769.asc  |
|  120   |    4700    | 7/26/22 3:36  | 7/26/22 18:26 | 7/26/22 19:04 | 7/27/22 3:43  | 7/27/22 3:43  | 121016 |      Good       |  120m_4700.XML  |
|  125   | ADCP 7637  | 7/26/22 3:32  | 7/26/22 19:08 | 7/26/22 19:41 | 7/27/22 6:43  | 7/27/22 6:42  | 48387  |      Good       |    1000.000     |
|  135   |    2451    | 7/26/22 3:31  | 7/26/22 18:26 | 7/26/22 19:04 | 7/27/22 5:43  | 7/27/22 5:41  | 121046 |  Bad Pressure   |  135m_2451.asc  |
|  155   |    4701    | 7/26/22 3:30  | 7/26/22 18:26 | 7/26/22 19:04 | 7/27/22 5:51  | 7/27/22 5:51  | 121048 |      Good       |  155m_4701.XML  |
| 38 mab |   11380    | 7/25/22 21:47 | 7/26/22 18:26 | 7/26/22 19:04 | 7/27/2022 n/a | 7/27/22 16:45 | 96970  |      Good       | 4661m_11380.asc |
| 38 mab |   11381    | 7/25/22 21:47 | 7/26/22 18:26 | 7/26/22 19:04 | 7/27/2022 n/a | 7/27/22 17:05 | 96974  |      Good       | 4661m_11381.asc |
```

```{table} WHOTS-17 mooring ADCP deployment and configuration information. All times are in UTC (mm/dd/yy hh:mm:ss).
:name: table-9
:widths: auto
:align: center

|          **-**          | **ADCP S/N 13917** | **ADCP S/N 7637**  |
| :---------------------: | :----------------: | :----------------: |
|     Frequency (kHz)     |        600         |        300         |
|  Number of Depth Cells  |         25         |         30         |
|   Depth Cell Size (m)   |        2 m         |        4 m         |
|   Pings per Ensemble    |         80         |         40         |
| Time per Ensemble (min) |       10 min       |       10 min       |
|   Time per Ping (sec)   |       2 sec        |       4 sec        |
|   Time of First Ping    | 08/25/21, 05:50:00 | 08/25/21, 06:07:00 |
| Transducer 1 Spike Time | 08/25/21, 06:10:00 | 08/25/21, 06:17:00 |
| Transducer 2 Spike Time | 08/25/21, 06:10:15 | 08/25/21, 06:17:15 |
| Transducer 3 Spike Time | 08/25/21, 06:10:30 | 08/25/21, 06:17:30 |
| Transducer 4 Spike Time | 08/25/21, 06:10:45 | 08/25/21, 06:17:45 |
|  Ice Spike Time Begin   | 08/25/21, 06:20:00 | 08/25/21, 06:27:00 |
|   Ice Spike Time End    | 08/25/21, 06:22:00 | 08/25/21, 06:29:49 |
|      Time in Water      |   08/25/20:39:00   | 08/25/21, 21:00:00 |
|        Depth (m)        |       47.5 m       |       125 m        |
```

```{table} WHOTS-17 mooring ADCP recovery information. All times are in UTC (mm/dd/yy hh:mm:ss).
:name: table-10
:widths: auto
:align: center

|            **-**             | **ADCP S/N 13917** | **ADCP S/N 7637**  |
| :--------------------------: | :----------------: | :----------------: |
|       Frequency (kHz)        |        600         |        300         |
|    Number of Depth Cells     |         25         |         30         |
|     Depth Cell Size (m)      |        2 m         |        4 m         |
|      Pings per Ensemble      |         80         |         40         |
|   Time per Ensemble (min)    |       10 min       |       10 min       |
|     Time per Ping (sec)      |       2 sec        |       4 sec        |
|      Time of Last Ping       | 7/27/22, 06:53:00  | 7/27/22, 06:43:00  |
|   Transducer 1 Spike Time    |      20:13:00      |      20:10:05      |
|   Transducer 2 Spike Time    |      20:13:15      |      20:10:20      |
|   Transducer 3 Spike Time    |      20:13:30      |      20:10:35      |
|   Transducer 4 Spike Time    |      20:13:45      |      20:10:50      |
|      Time in the Water       | 08/25/21, 20:39:00 | 08/25/21, 21:00:00 |
|      Time out of Water       | 07/26/22, 03:45:00 | 07/26/22, 03:32:00 |
|       Time of spike          | 07/26/22, 19:08:00 | 07/26/22, 19:08:00 |
|     Time Logging Stopped     | 07/27/22, 06:53:00 | 07/27/22, 06:43:00 |
| Instrument Time when Stopped | 07/27/22, 07:00:16 | 07/27/22, 06:42:45 |
|          Depth (m)           |       47.5 m       |       125 m        |
```

The RDI 300 kHz Workhorse Sentinel ADCP, SN 7637, was deployed at 125 m with
transducers facing upwards with an additional external battery pack. This
instrument was set to ping at 4-second intervals for 160 seconds every 10
minutes, and the burst sampling was designed to minimize aliasing by occasional
large ocean swell orbital motions. The bin size was set for 4 m. The total
number of ensemble records was 48,387. The first ensemble was on 08/25/2021 at
06:07:00 and the last was on 07/27/2022 at 06:43 (see {numref}`table-9`,
{numref}`table-10`, and {ref}`/appendices.md#whots-17-300-khz-serial-7367` for
more configuration). This instrument also measured temperature.

The RDI 600 kHz Workhorse Sentinel ADCP, SN 13917, was deployed at 47.5 m with
transducers facing upwards with an additional external battery pack. The
instrument was set to ping at 2-second intervals for 160 seconds every 10
minutes, and the burst sampling was designed to minimize aliasing by occasional
large ocean swell orbital motions. The bin size was set for 2 m. The total
number of ensemble records was 48,391. The first ensemble was on 08/25/2021 at
05:50:00, and the last was on 07/27/2022 at 06:53:00 (see {numref}`table-9`
, {numref}`table-10`, and {ref}`/appendices.md#whots-17-600-khz-serial-13917`
for more configuration). This instrument also measured temperature.

The two VMCMs, SN 0035 and 0058, were deployed at 10 m and 30 m depth,
respectively. The instruments were prepared for deployment by the WHOI/UOP
group and set to sample at 1-minute interval. These instruments also
measured temperature.

All WHOTS-17 instruments on the mooring were successfully recovered. Most of
the instruments had some degree of biofouling, with the heaviest fouling near
the surface. Fouling extended down to the ADCP at 125 m, although it was minor
at that depth.

All MicroCATs except for the one at 155 m were in good condition after
recovery. MicroCAT SN 3620 (55 m) had barnacles partially blocking the top of
its conductivity cell, and SN 6892 (7 m) was recovered with fishing
line wrapped around the instrument and the chain. The MicroCAT SN 4701
at 155 m was recovered missing its sensor guard and with a bent conductivity
cell.

After recovery and before stopping recording, a bag of ice was placed in
contact with each MicroCAT temperature sensor, to produce a spike in the data
as a reference point to check the instrument’s clock. The data from all
instruments were downloaded at the UH lab. {numref}`table-8` gives the post-deployment
information for the C-T instruments; more details are in
{ref}`/5_section.md#microcat-data-processing-procedures`, and
{ref}`/6_section.md#microcat-data`.

The data from the upward-looking 300 kHz ADCP at 125 m were good; the
instrument was pinging upon recovery. There appears to be no obviously
questionable data from this ADCP at this time, apart from near-surface
side-lobe interference. At the time when logging was stopped
({numref}`table-10`), the instrument time was 15 sec behind UTC.
