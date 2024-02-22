# Dataset Overview

This repository contains the dataset used in our research, as outlined in the associated publication. The dataset comprises data from 21 participants (P1-P21), with each participant's data segregated into specific sessions and blocks as per the study's design. The sessions include non-manipulated sessions and an orientation manipulation session, each containing multiple blocks with CSV files representing individual trials.

## Directory Structure

- **Participants (P1-P21):** Each directory named P1 to P21 corresponds to a participant in the study.
  - **NM_1 (Session 1 - Non-Manipulated):** Contains 7 folders (Block 1 to Block 7), with each folder housing 32 CSV files for the trials conducted in this session.
  - **OM (Session 2 - Orientation Manipulation):** Comprises 2 folders (Block 1 and Block 2), each containing 40 CSV files for the trials within this session.
  - **NM_3 (Session 3 - Non-Manipulated):** Includes 5 folders (Block 1 to Block 5), with each folder containing 16 CSV files for the trials in this session.

Each session and block are designed to capture specific interaction patterns and responses as detailed in our study.

## CSV File Format

Each CSV file within the blocks follows a standardized format to record trial data:

- **Columns:**
  - `timestamp`: The time at which the data was recorded, in milliseconds.
  - `true_hand_pos_X`: The X coordinate of the true hand/controller position, tracked by VR in meters.
  - `true_hand_pos_Y`: The Y coordinate of the true hand/controller position, tracked by VR in meters.
  - `true_hand_pos_Z`: The Z coordinate of the true hand/controller position, tracked by VR in meters.

## Usage

The dataset is structured to facilitate analysis across different sessions and blocks, enabling a comprehensive examination of participant responses under varied conditions. Refer to the publication for detailed insights into the study's design and findings.
