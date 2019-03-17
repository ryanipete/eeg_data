# EEG Data Samples

A collection of data recorded using the OpenBCI Cyton board.

Data is collected using a custom Python script. Connection to the headset and conversion of data from the Cyton headset is handled using OpenBCI's [Python library](https://github.com/OpenBCI/OpenBCI_Python). The 60 Hz notch filter is enabled (by calling the [`enable_filters()`](https://github.com/OpenBCI/OpenBCI_Python/blob/81caa0ca4c2862cfb7f9e5f28f049576e7718cae/openbci/cyton.py#L497) method on `OpenBCICyton`), but data is otherwise unprocessed. 
