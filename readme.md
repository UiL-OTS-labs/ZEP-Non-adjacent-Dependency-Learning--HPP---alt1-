Experiment:
        Non-adjacent Dependency Learning (HPP)

Description:
        Purpose of this headturn preference experiment is to see whether an 
        infant participant can detect a difference between two types of 
        auditory stimuli. The infant sits on the caregiver's lap facing a 
        wall on which a green light, an invisible speaker and a camera is 
        mounted. On each side wall a red light and an invisible speaker are 
        mounted. In this implementation there is a familiarization phase and
        a test phase. For each trial in the test phase the infant's attention 
        is drawn to one the side lights (blinking). When the infant looks at 
        the blinking light a sequence of sound stimuli starts and a timer runs
        as long as the infant keeps looking at the blinking light. The trial 
        ends when the infant looks away too long (or when a particular number
        of stimuli have been presented). In the familiarization phase that 
        precedes the test phase a similar contingency procedure is used but 
        only for the lights; the sound stimuli once started continue until 
        all have been presented. Output test phase: looking time. Output 
        familiarization phase: total looking time.

        In this implementation two participant groups are defined. Each group
        will be familiarized with a different set of stimuli (language). In
        the test phase half of the stimuli will be taken from one set and the
        other half will be taken from the other set. The stimuli in a test
        trial are sequences of different versions of the same type (language)
        rather than sequences of the same stimulus.

        The main difference between this implementation and the regular nadl
        is that here the familiarization phase also includes some 
        'ungrammatical' items.

Author:
        Theo Veenker <theo.veenker@beexy.nl>

Client:
        -

Supervisor:
        -

References:
        Kerkhoff, A.O., Bree, E.H. de, Klerk, M. de & Wijnen, F.N.K. (2012).
          Non-adjacent dependency learning in infants at familial risk of 
          dyslexia.
          Journal of child language, to appear.


For information on running the experiment and extracting the experiment
results please go the the Zep website at http://www.beexy.nl/zep and check 
out the documentation section. There you'll also find explanations and 
instructions that help you understand and modify a Zep experiment.


DISCLAIMER

This experiment script is released under the terms of the GNU General Public
License (see http://www.gnu.org/licenses/gpl-2.0.html). It is distributed in
the hope that it will be useful, but with absolutely no warranty. It is your
responsibility to carefully study and test the script before using it with 
real participants.
