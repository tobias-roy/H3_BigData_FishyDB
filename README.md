# H3_BigData_FishyDB

## Overview

H3_BigData_FishyDB is a school project that implements an Extract, Load, Transform (ELT) Pipeline for handling big data related to fisheries. The project utilizes various technologies, including PolygonAPI, MongoDB Atlas, Airbyte, Supabase, and Metabase.

## Table of Contents

- [Project Components](#project-components)
- [Setup](#setup)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Project Components

### 1. PolygonAPI

[PolygonAPI](https://polygon.io/) is used for extracting financial market data, providing real-time and historic market data.

### 2. MongoDB Atlas

[MongoDB Atlas](https://www.mongodb.com/cloud/atlas) serves as the database for storing and managing the extracted data. MongoDB Atlas is a fully-managed cloud database service.

### 3. Airbyte

[Airbyte](https://airbyte.io/) is employed for the data integration phase, helping to facilitate the movement of data between various sources, such as PolygonAPI, and the MongoDB Atlas database.

### 4. Supabase

[Supabase](https://supabase.io/) is utilized as a complementary data platform, offering features like real-time APIs and authentication services.

### 5. Metabase

[Metabase](https://www.metabase.com/) is the chosen tool for transforming and visualizing the data. It provides a user-friendly interface for creating dashboards and exploring data insights.

## Setup

To set up the project locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/H3_BigData_FishyDB.git
   cd H3_BigData_FishyDB
