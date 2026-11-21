# CAD 工具/Tool
基于 MFC 开发的 64 位绘图程序，可自由切换中文版或英文版。
A 64-bit drawing application developed with MFC. Switch between the Chinese and English editions easily.
## 功能/Function
- 可用于常规机械制图，适合中小企业使用。
- Suitable for small and medium-sized businesses for mechanical drawing.
- 具有初等函数绘图功能，适合中学生使用。
- The basic function plotting features is suitable for middle school students
## 运行说明/Instructions
- 架构/Architecture：x64
- 支持系统/Supported system：Windows 10 / Windows 11
- 运行方式：直接双击 cad.exe
- Run mode: Double click cad.exe
- 依赖库/Dependency library：
  - mfc140u.dll
  - msvcp140.dll
  - vcruntime140.dll
  - vcruntime140_1.dll
> 请保证 dll 文件和 cad.exe 在同一个文件夹，不要单独移动 dll。
> Make sure the dll file and cad.exe are in the same folder, don't move the dll by itself.

## 已知说明/Other Instructions
- 当前为动态链接版本，依赖上述运行库；
- It's a dynamic link version and depends on the runtime libraries mentioned above.
- 请勿删除同目录下的 dll 文件，否则会提示缺少组件无法启动；
- Do not delete the DLL files in the same directory, or it will say a component is missing and won't start.
- 程序仅在 x64 系统下可用，不支持 32 位 Windows。
- The program only works on x64 Windows and doesn't support 32-bit Windows.

## 版本信息/Version
Version v1.0
