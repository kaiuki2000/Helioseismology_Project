                  *** Global Oscillations at Low Frequencies ***

The data of this set correspond to 183 days, from 1996 April 11th, to 1996
October 10th included. Data are given separately for the 2 detectors,
referred to as Photo Multiplier 1 and Photo Multiplier 2 of the GOLF Main
Channel. The data files for each Photo-Multiplier are in ASCII format,
compressed and put together in a tar file. The uncompressed files should be
read across then down. The total number of points is 790560, corresponding
to a sampling time of 20s. The first point corresponds to an integration
centered on 00h00mn9.5sec of UT time aboard SOHO.

     Calibrate  (velocity) time series:
     ***********************************
     To deduce velocities from intensities is not trivial. Some steps are
     quite obvious, like the SUN-SOHO distance normalisation, but others
     involved some coupling between various effects (orbital or purely
     thermal for example). To deal with all parameters together is not a
     simple task, and some assumptions are required. For example, the
     extrapolation of the pre-launch tests to flight conditions may or may
     not be considered. Two separate groups from our consortium have
     developed their own velocity calibration process, from which 
     oscillation velocities time series are given here.

        o Method 1 (Paris)
          Calibration based on the magnetic modulation of the signal
          The amplitude of the intensity variation induced by a Doppler
          shift of the sodium lines, is proportional to the slopes of the
          wings around the operating points. Such local slopes can be
          estimated thanks to an instrumental magnetic modulation. The
          velocity can be inferred knowing the amplitude of the magnetic
          modulation.
          Data from Photo-Multiplier 1 and Photo-Multiplier 2.

        o Method 2 (Los Angles)
          Calibration based on the modeling of the photometric response of
          the instrument.
          The values of the measured intensities are parameterised as well
          as possible, and the system is eventually solved as a function of
          the orbital velocity.
          Data from Photo-Multiplier 1 and Photo-Multiplier 2.

           