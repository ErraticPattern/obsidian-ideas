---
creation date: 2024-11-17 20:05
aliases: 
tags:
  - baby
modification date: Sunday, 17th November 2024, 20:05:28
id:
---
---

## Parent note
[[Study Struct]]---
## Backlinking


---
# Info Struct
The `info` struct is designed to store metadata and file paths essential for neuroimaging data analysis, particularly in studies involving EEG data. It organizes entities, subjects, tasks, file extensions, data file paths, and other relevant information required for data processing and analysis.
## Fields

### `entities`

- **Type**: Array of strings
- **Description**: Specifies the key entities used in the dataset, typically following the Brain Imaging Data Structure (BIDS) format. Common entities include:
    - `'sub'`: Subject identifier
    - `'ses'`: Session identifier
    - `'run'`: Run number
    - `'task'`: Task name

### `subjects`

- **Type**: Cell array of strings
- **Description**: Contains a list of subject identifiers included in the study.
    - **Example**: `{ 'sub-01', 'sub-02', 'sub-03', ... }`

### `sessions`

- **Type**: Cell array of strings
- **Description**: Lists session identifiers if multiple sessions are used per subject.
    - **Example**: `{ 'ses-01', 'ses-02' }`
    - **Note**: This field can be empty if sessions are not applicable.

### `tasks`

- **Type**: Cell array of strings
- **Description**: Contains the names of tasks performed during data acquisition.
    - **Example**: `{ 'rest', 'task-motor', 'task-memory' }`

### `runs`

- **Type**: Cell array of strings
- **Description**: Lists run identifiers if multiple runs are conducted per task or session.
    - **Example**: `{ 'run-01', 'run-02' }`
    - **Note**: This field can be empty if runs are not applicable.

### `suffixes`

- **Type**: Cell array of strings
- **Description**: Specifies the data types or file suffixes used in the dataset.
    - **Example**: `{ 'eeg', 'channels', 'events', 'electrodes', 'scans' }`

### `extensions`

- **Type**: Cell array of strings
- **Description**: Lists the file extensions associated with the data files.
    - **Example**: `{ '.eeg', '.vhdr', '.vmrk', '.tsv', '.nii.gz' }`

### `eeg_data`

- **Type**: Cell array of strings
- **Description**: Contains full paths to the EEG data files for all subjects, sessions, runs, and tasks.
    - **Example**: `{ '/path/to/sub-01_task-rest_eeg.eeg', '/path/to/sub-01_task-rest_eeg.vhdr', ... }`

### `specific`

- **Type**: Struct
- **Description**: Holds specific identifiers for the current dataset being processed.
    - **Fields**:
        - `sub`: Current subject identifier (e.g., `'sub-01'`)
        - `ses`: Current session identifier (e.g., `'ses-01'`)
        - `run`: Current run identifier (e.g., `'run-01'`)
        - `task`: Current task name (e.g., `'rest'`)

### `pip_name`

- **Type**: String
- **Description**: Name of the data processing pipeline used for analysis.
    - **Example**: `'pipeline-preprocessing-v1'`

### `ana_name`

- **Type**: String
- **Description**: Name of the specific analysis being performed.
    - **Example**: `'analysis-rest-vs-task'`

### `eeg_fname`

- **Type**: Cell array of strings
- **Description**: Paths to EEG data files for the specific subject, session, run, and task defined in `specific`.
    - **Example**: `{ '/path/to/sub-01_task-rest_eeg.eeg', '/path/to/sub-01_task-rest_eeg.vhdr', ... }`

### `events_fname`

- **Type**: Cell array of strings
- **Description**: Paths to event files associated with the EEG data.
    - **Example**: `{ '/path/to/sub-01_task-rest_events.tsv' }`

### `channels_fname`

- **Type**: Cell array of strings
- **Description**: Paths to channel information files.
    - **Example**: `{ '/path/to/sub-01_task-rest_channels.tsv' }`

### `electrodes_fname`

- **Type**: Cell array of strings
- **Description**: Paths to electrode location files.
    - **Note**: May be empty if electrode information is embedded elsewhere.

---
# Notes

## Definition

## Associations

## Interpretation

---
## Links
- [Google Search](https://www.google.com/search?q=Info+Struct)

---
# Bibliography
+ 