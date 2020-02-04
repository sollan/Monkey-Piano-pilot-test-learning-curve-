# Monkey-Piano-pilot-test-learning-curve-

Both auditory perceptual and motor training have been found to lead to changes in underlying neural activity [1, 2]. However, there has been little research on single trial variations of neural activity during auditory learning [3], which has implications for brain-computer interfaces and may help us better understand the encoding and storage of auditory and motor memory. Moreover, auditory and motor processes are known to be closely linked [4, 5]. Therefore, a paradigm that allows the comparison of neural correlates during related perceptual and motor tasks might provide insight into the interaction between sensory and motor systems. In this study, we will analyze the EEG event-related potential components during the perceptual and motor learning of novel music stimuli to identify markers for auditory-related learning.

### Instructions for this pilot study paradigm

(`psychopy` and `pygame` needed. In the case that the experiment doesn't have sound / gives "output device out of range" or similar errors, for mac, you might need to set up midi output using Audio MIDI setup, and for Linux, you might need to configure virtual MIDI using Alsa and fluidsynth --> contact experimenter for support!)

In this pilot experiment, you'll hear some melodies (8 notes long, 4 different notes used), and you need to reproduce the melodies using keys g,h,j,k on your keyboard. There are 3 melodies in total, and you'll hear each melody 15 times. It goes like this: beep, you hear melody A once, beep, you try to play it out on your keyboard; beep, you hear melody A again, etc. until after 15 times you start with melody B, and then melody C. _ONLY_ press the keys after hearing the "replay" beep. Your responses will help us decide on the number of repititions for each melody used in the final paradigm, in order to minimize fatigue and ensure optimal learning.

### Preliminary study design

After a practice trial where the subject is familiarized with the experiment set-up, the subject will be presented with 10 midi-generated piano melodies in random order. The stimuli are delivered via headphones. Every melody is 12 notes long and includes 4 distinct pitches. Each note in the melody has a duration of 500 ms and is followed by 500 ms of silence. After hearing a melody once, the subject is required to reproduce the melody as accurately as possible using a 4-key keyboard placed on the table in front of them with 4 right-hand digits. The listening and reproduction trial is then repeated for the same melody. Each melody involves 10 listening and 10 reproduction trials performed intermittently. A piano note of 500 ms serves as auditory cue for the onset of every listening and reproduction trial. After finishing all trials for a given melody, the subject may have a self-paced break.

We plan to record data from 20 healthy subjects for this study. Electroencephalography (EEG) (Brain Products actiChamp amplifier with 32 active gel-based electrodes) is applied to record neural activity. Electrooculography (EOG) signals will be recorded through 3 channels simultaneously for later artifact removal. In addition, subjects will be required to reproduce the music stimuli by pressing the keys on a 4-key keyboard. The accuracy and timing precision will be recorded. Moreover, we will collect demographic data from the subject about their age, sex, music experience, and previous experience with BCI studies, if any.

##### References:

[1] Alain, C., Snyder, J. S., He, Y., & Reinke, K. S. (2007). Changes in auditory cortex parallel rapid perceptual learning. Cerebral Cortex, 17(5), 1074-1084. https://doi.org/10.1093/cercor/bhl018
</br>
[2] Ross, B., Barat, M., & Fujioka, T. (2017). Sound-making actions lead to immediate plastic changes of neuromagnetic evoked responses and induced β-band oscillations during perception. Journal of Neuroscience, 37(24), 5948-5959. https://doi.org/10.1523/JNEUROSCI.3613-16.2017
</br>
[3] de Souza, A. C. S., Yehia, H. C., Sato, M. A., & Callan, D. (2013). Brain activity underlying auditory perceptual learning during short period training: simultaneous fMRI and EEG recording. BMC neuroscience, 14(1), 8. https://doi.org/10.1186/1471-2202-14-8
</br>
[4] Bangert, M., & Altenmüller, E. O. (2003). Mapping perception to action in piano practice: a longitudinal DC-EEG study. BMC neuroscience, 4(1), 26. https://doi.org/10.1186/1471-2202-4-26
</br>
[5] Haueisen, J., & Knösche, T. R. (2001). Involuntary motor activity in pianists evoked by music perception. Journal of cognitive neuroscience, 13(6), 786-792. https://doi.org/10.1162/08989290152541449
