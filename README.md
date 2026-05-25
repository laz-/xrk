# xrk
Python [AiM](https://www.aim-sportline.com) XRK file reader.

**Note:** This library was written before better options existed. For new projects, use
[libxrk](https://github.com/m3rlin45/libxrk) (cross-platform, actively maintained) and
[Inferno Analyzer](https://github.com/m3rlin45/motorsports_data_notebook) for full
telemetry analysis. `xrk.py` is kept here for reference.

---

## Old Content

Once upon a time, AiM released a DLL to read their proprietary data file format
and provided some sample code for import into Matlab. That article can be found
[here](https://www.aim-sportline.com/download/software/doc/how-to-access-xrk-files-data-without-aim-software_101.pdf)

I don't use Matlab, but I can slap together Python, so here we are. This
repository contains a Python wrapper for the AiM provided DLL.

## Dependencies

On Windows, `xrk.py` uses the bundled AiM DLL directly. On macOS/Linux, install
[libxrk](https://github.com/m3rlin45/libxrk):

```
pip install libxrk
```

## Examples
Check out [examples.ipynb](examples.ipynb) in your browser or spin it up on
your computer in Jupyter notebook.
