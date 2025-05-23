# PLP_Database
  Overview:
    This SQL script creates a comprehensive Clinic Management System database designed for hospitals and clinics. It covers patient management, appointments, medical records, billing, staff, and more.
    Features:
    - Patient, doctor, staff, and department management
    - Appointment scheduling with conflict prevention
    - Medical records and prescription tracking
    - Billing and insurance claim support
    - Status and gender lookup tables for data consistency
    - Soft delete support for most tables
    - Audit fields (created/updated by and timestamps)
    - Indexes for performance optimization
    #
    Usage:
    1. Run this script in your MySQL/MariaDB environment.
    2. The script will drop and recreate the `clinic_management` database.
    3. All tables, constraints, and indexes will be created automatically.
    4. Populate tables with your data as needed.
    #
    Notes:
    - Foreign key constraints are enforced for data integrity.
    - Default values and constraints are set for common fields.
    - Modify or extend tables as required for your clinic's needs.
    Author: [MARTIN KAMAU]
    Date: [23/5/2025]
    */
