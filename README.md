<div id="top">

<!-- HEADER STYLE: CLASSIC -->
<div align="left">

<!-- <img src="Picamera-OpenCV.png" width="30%" style="position: relative; top: 0; right: 0;" alt="Project Logo"/> -->

# PICAMERA-OPENCV

<em>Transform Vision into Action with Real-Time Precision</em>

<!-- BADGES -->
<img src="https://img.shields.io/github/last-commit/code0-god/Picamera-OpenCV?style=flat&logo=git&logoColor=white&color=0080ff" alt="last-commit">
<img src="https://img.shields.io/github/languages/top/code0-god/Picamera-OpenCV?style=flat&color=0080ff" alt="repo-top-language">
<img src="https://img.shields.io/github/languages/count/code0-god/Picamera-OpenCV?style=flat&color=0080ff" alt="repo-language-count">

<em>Built with the tools and technologies:</em>

<img src="https://img.shields.io/badge/Markdown-000000.svg?style=flat&logo=Markdown&logoColor=white" alt="Markdown">
<img src="https://img.shields.io/badge/Threads-000000.svg?style=flat&logo=Threads&logoColor=white" alt="Threads">
<img src="https://img.shields.io/badge/GNU%20Bash-4EAA25.svg?style=flat&logo=GNU-Bash&logoColor=white" alt="GNU%20Bash">
<img src="https://img.shields.io/badge/C++-00599C.svg?style=flat&logo=C++&logoColor=white" alt="C++">
<img src="https://img.shields.io/badge/CMake-064F8C.svg?style=flat&logo=CMake&logoColor=white" alt="CMake">
<img src="https://img.shields.io/badge/Python-3776AB.svg?style=flat&logo=Python&logoColor=white" alt="Python">
<img src="https://img.shields.io/badge/OpenCV-5C3EE8.svg?style=flat&logo=OpenCV&logoColor=white" alt="OpenCV">

</div>
<br>

---

## Table of Contents

- [Overview](#overview)
- [Getting Started](#getting-started)
    - [Prerequisites](#prerequisites)
    - [Installation](#installation)
    - [Usage](#usage)
    - [Testing](#testing)
- [Features](#features)
- [Project Structure](#project-structure)
    - [Project Index](#project-index)
- [Roadmap](#roadmap)

---

## Overview

Picamera-OpenCV is an advanced developer toolkit that enables real-time video streaming and processing on Raspberry Pi 5, seamlessly integrating Picamera2 with OpenCV for live image capture and analysis. It provides a robust foundation for AI, FPGA, and blockchain-enabled vision systems.

**Why Picamera-OpenCV?**

This project streamlines real-time video handling and inter-process communication, empowering developers to build scalable, hardware-accelerated vision applications. The core features include:

- **🛠️** **Real-time Streaming:** Continuous frame capture, display, and FPS monitoring for live video applications.
- **🌐** **Web-based Interface:** Easy viewing and control through a web interface, with reliable process management.
- **🔄** **Shared Memory Communication:** Efficient data exchange between Python and C++ components, ensuring minimal latency.
- **🚀** **Extensibility:** Designed to support future AI validation, FPGA modules, and blockchain integrations.
- **🔧** **Robust Build & Cleanup:** Automated scripts for environment setup and cleanup, ensuring system stability.

---

## Features

|      | Component       | Details                                                                                     |
| :--- | :-------------- | :------------------------------------------------------------------------------------------ |
| ⚙️  | **Architecture**  | <ul><li>Modular design separating camera capture, image processing, and display</li><li>Uses OpenCV for image analysis</li><li>Leverages CMake for build configuration</li></ul> |
| 🔩 | **Code Quality**  | <ul><li>Consistent C++ coding style with header files and source separation</li><li>Python scripts for automation and testing</li><li>Clear directory structure with dedicated modules</li></ul> |
| 📄 | **Documentation** | <ul><li>Basic README with project overview</li><li>Comments within codebase</li><li>No extensive external docs or wiki</li></ul> |
| 🔌 | **Integrations**  | <ul><li>Integrates with Raspberry Pi Camera Module via `picamera` or V4L2</li><li>Uses OpenCV for image processing tasks</li><li>Builds with CMake, includes shell scripts for setup</li></ul> |
| 🧩 | **Modularity**    | <ul><li>Separate modules for camera interface, image processing, and display</li><li>Header files define interfaces, enabling easy extension</li></ul> |
| 🧪 | **Testing**       | <ul><li>Includes camera test scripts (`camera_test`)</li><li>Python scripts for automated testing</li><li>Limited unit tests; mainly functional tests</li></ul> |
| ⚡️  | **Performance**   | <ul><li>Real-time image capture and processing</li><li>Uses multithreading (`Threads`) for concurrent capture and processing</li><li>Optimized with OpenCV's efficient functions</li></ul> |
| 🛡️ | **Security**      | <ul><li>No explicit security features implemented</li><li>Potential concerns with camera access permissions</li></ul> |
| 📦 | **Dependencies**  | <ul><li>Build system: CMake (`CMakeLists.txt`)</li><li>Libraries: OpenCV, Threads</li><li>Language: C++, Python</li></ul> |

---

## Project Structure

```sh
└── Picamera-OpenCV/
    ├── CMakeLists.txt
    ├── README.md
    ├── include
    │   └── shared_memory.h
    ├── scripts
    │   └── camera_capture.py
    ├── src
    │   └── shared_memory.cpp
    ├── streaming.sh
    └── test
        └── camera_test.cpp
```

---

### Project Index

<details open>
	<summary><b><code>PICAMERA-OPENCV/</code></b></summary>
	<!-- __root__ Submodule -->
	<details>
		<summary><b>__root__</b></summary>
		<blockquote>
			<div class='directory-path' style='padding: 8px 0; color: #666;'>
				<code><b>⦿ __root__</b></code>
			<table style='width: 100%; border-collapse: collapse;'>
			<thead>
				<tr style='background-color: #f8f9fa;'>
					<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
					<th style='text-align: left; padding: 8px;'>Summary</th>
				</tr>
			</thead>
				<tr style='border-bottom: 1px solid #eee;'>
					<td style='padding: 8px;'><b><a href='https://github.com/code0-god/Picamera-OpenCV/blob/master/CMakeLists.txt'>CMakeLists.txt</a></b></td>
					<td style='padding: 8px;'>- Sets up the build configuration for a media integrity verification project, defining dependencies and compilation parameters<br>- It orchestrates the compilation of a camera testing application that leverages OpenCV for image processing and shared memory for data exchange, ensuring the application integrates seamlessly within the overall system architecture.</td>
				</tr>
				<tr style='border-bottom: 1px solid #eee;'>
					<td style='padding: 8px;'><b><a href='https://github.com/code0-god/Picamera-OpenCV/blob/master/README.md'>README.md</a></b></td>
					<td style='padding: 8px;'>- Facilitates real-time video streaming by integrating Picamera2 with OpenCV on Raspberry Pi 5, enabling continuous frame capture, display, and FPS monitoring<br>- Serves as the core component for live image processing within the project’s AI and hardware integration architecture, supporting future enhancements like AI validation, FPGA modules, and blockchain connectivity.</td>
				</tr>
				<tr style='border-bottom: 1px solid #eee;'>
					<td style='padding: 8px;'><b><a href='https://github.com/code0-god/Picamera-OpenCV/blob/master/streaming.sh'>streaming.sh</a></b></td>
					<td style='padding: 8px;'>- Facilitates the initialization and cleanup of the web streaming environment by terminating conflicting processes, clearing shared memory, and launching the Python-based camera capture script<br>- Ensures a clean state for reliable real-time video streaming, integrating process management with the core streaming workflow within the overall system architecture.</td>
				</tr>
			</table>
		</blockquote>
	</details>
	<!-- test Submodule -->
	<details>
		<summary><b>test</b></summary>
		<blockquote>
			<div class='directory-path' style='padding: 8px 0; color: #666;'>
				<code><b>⦿ test</b></code>
			<table style='width: 100%; border-collapse: collapse;'>
			<thead>
				<tr style='background-color: #f8f9fa;'>
					<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
					<th style='text-align: left; padding: 8px;'>Summary</th>
				</tr>
			</thead>
				<tr style='border-bottom: 1px solid #eee;'>
					<td style='padding: 8px;'><b><a href='https://github.com/code0-god/Picamera-OpenCV/blob/master/test/camera_test.cpp'>camera_test.cpp</a></b></td>
					<td style='padding: 8px;'>- Facilitates real-time acquisition and processing of video frames via shared memory, serving as a core component in a larger computer vision and data verification pipeline<br>- It continuously reads frames, computes performance metrics, and provides a foundation for integrating AI-based analysis, FPGA hardware interactions, and blockchain-based metadata recording, supporting secure and efficient video data handling within the system architecture.</td>
				</tr>
			</table>
		</blockquote>
	</details>
	<!-- include Submodule -->
	<details>
		<summary><b>include</b></summary>
		<blockquote>
			<div class='directory-path' style='padding: 8px 0; color: #666;'>
				<code><b>⦿ include</b></code>
			<table style='width: 100%; border-collapse: collapse;'>
			<thead>
				<tr style='background-color: #f8f9fa;'>
					<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
					<th style='text-align: left; padding: 8px;'>Summary</th>
				</tr>
			</thead>
				<tr style='border-bottom: 1px solid #eee;'>
					<td style='padding: 8px;'><b><a href='https://github.com/code0-god/Picamera-OpenCV/blob/master/include/shared_memory.h'>shared_memory.h</a></b></td>
					<td style='padding: 8px;'>- Facilitates shared memory communication between Python and C++ components, enabling efficient transfer of camera frames captured by Picamera2<br>- It manages the creation, validation, and cleanup of shared memory segments, ensuring seamless and synchronized data exchange within the overall architecture<br>- This core class underpins real-time image processing and inter-process communication in the project.</td>
				</tr>
			</table>
		</blockquote>
	</details>
	<!-- src Submodule -->
	<details>
		<summary><b>src</b></summary>
		<blockquote>
			<div class='directory-path' style='padding: 8px 0; color: #666;'>
				<code><b>⦿ src</b></code>
			<table style='width: 100%; border-collapse: collapse;'>
			<thead>
				<tr style='background-color: #f8f9fa;'>
					<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
					<th style='text-align: left; padding: 8px;'>Summary</th>
				</tr>
			</thead>
				<tr style='border-bottom: 1px solid #eee;'>
					<td style='padding: 8px;'><b><a href='https://github.com/code0-god/Picamera-OpenCV/blob/master/src/shared_memory.cpp'>shared_memory.cpp</a></b></td>
					<td style='padding: 8px;'>- Facilitates shared memory management within the system by enabling creation, access, and cleanup of shared memory segments<br>- Supports inter-process communication through memory mapping, ensuring efficient data sharing and synchronization across different components of the architecture<br>- Serves as a foundational utility for enabling seamless data exchange in a multi-process environment.</td>
				</tr>
			</table>
		</blockquote>
	</details>
	<!-- scripts Submodule -->
	<details>
		<summary><b>scripts</b></summary>
		<blockquote>
			<div class='directory-path' style='padding: 8px 0; color: #666;'>
				<code><b>⦿ scripts</b></code>
			<table style='width: 100%; border-collapse: collapse;'>
			<thead>
				<tr style='background-color: #f8f9fa;'>
					<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
					<th style='text-align: left; padding: 8px;'>Summary</th>
				</tr>
			</thead>
				<tr style='border-bottom: 1px solid #eee;'>
					<td style='padding: 8px;'><b><a href='https://github.com/code0-god/Picamera-OpenCV/blob/master/scripts/camera_capture.py'>camera_capture.py</a></b></td>
					<td style='padding: 8px;'>- Facilitates real-time camera streaming and shared memory integration within a web-based interface, enabling team members to view live footage seamlessly<br>- Manages camera initialization, frame capture, and communication with a background C++ process for additional image processing<br>- Ensures resource cleanup and system stability, providing a cohesive platform for live video sharing and concurrent processing in a distributed environment.</td>
				</tr>
			</table>
		</blockquote>
	</details>
</details>

---

## Getting Started

### Prerequisites

This project requires the following dependencies:

- **Programming Language:** CPP
- **Package Manager:** Cmake

### Installation

Build Picamera-OpenCV from the source and install dependencies:

1. **Clone the repository:**

    ```sh
    ❯ git clone https://github.com/code0-god/Picamera-OpenCV
    ```

2. **Navigate to the project directory:**

    ```sh
    ❯ cd Picamera-OpenCV
    ```

3. **Install the dependencies:**

**Using [cmake](https://isocpp.org/):**

```sh
❯ cmake . && make
```

### Usage

Run the project with:

**Using [cmake](https://isocpp.org/):**

```sh
./Picamera-OpenCV
```

### Testing

Picamera-opencv uses the {__test_framework__} test framework. Run the test suite with:

**Using [cmake](https://isocpp.org/):**

```sh
ctest
```

---

## Roadmap

- [X] **`Task 1`**: <strike>Implement feature one.</strike>
- [ ] **`Task 2`**: Implement feature two.
- [ ] **`Task 3`**: Implement feature three.

---

<div align="left"><a href="#top">⬆ Return</a></div>

---
