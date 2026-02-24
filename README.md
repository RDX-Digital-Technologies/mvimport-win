# mvimport

HIKROBOT MV Camera Control Python SDK for Windows x64 — fully bundled, no MVS SDK installation required.

All required DLLs and transport layer libraries are included inside the package.
Works out of the box after `pip install` on any Windows machine.

## Installation

```bash
pip install git+https://github.com/RDX-Digital-Technologies/mvimport-win.git
```

## Usage

```python
from mvimport.MvCameraControl_class import MvCamera
from mvimport.CameraParams_header import MV_CC_DEVICE_INFO_LIST
from mvimport.MvErrorDefine_const import MV_OK
```

## Requirements

- Python >= 3.7
- Windows (x64)
