---
                name: Charette
                about: A charette suggestion
                title: "CHR: VLF Receiver Data Ingress"
                labels: charette
                ---
                
                # Description
                Visualization and access of data produced by the VLF receiver sites. All data processing and visualization accomplished using vlfrx-tools software and standard Linux utilities. Processing and visualization functions don't require lots of memory and CPU resources.
                
                ## Suggested by:
                Jonathan Rizzo, KC3EEY, emuman100@gmail.com

                ## Additional comments:
                The following data ingress products are accomplished with utilities in vlfrx-tools:

1. Ingress of compressed vorbis VLF streams (like an audio stream) to natural radio event detector, signal property measurements, and rotating buffer signal storage (20 or so days of low band width storage on rotating buffer).
2. Ingress (via rsync operation) of VLF transmitter data, both png file plots and amplitude/absolute phase data.
3. Ingress (via rsync operation) of raw data (flac compressed).
4. (Future) Ingress of sferic time of group arrival (TOGA) data (textual data on 2-minute interval for processing and entry into sferic database)
5. Lightning stroke locations on a map (possible postgresql database with postgis for mapping) calculated from sferic data.
                 
