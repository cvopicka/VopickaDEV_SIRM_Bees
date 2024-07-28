# Database README

## Tables

### Configuration

- Config
  - ConfigID
  - Setting
  - Desc
  - Created
  - CreatedBy
  - Updated
  - UpdatedBy
  - Locked
  - LockedBy
- Config_User
  - UserID
  - ConfigID
  - Setting
  - Desc
  - Created
  - Updated
- Config_Location_Types
- Permissions (roles?)

## Users

- Users
  - UserID
  - UserType
  - Inactive
- Users_Contacts
- Users_Permissions

## Locations

- Locations
  - LocationID
  - Lat
  - Lon
- Locations_Contacts
  - LocationID
  - UserContactID
  - ContactType
  - StartDate
  - EndDate

## Hives

- Hives
  - BoxID
  - LocationID
  - Lat
  - Lon
  - Created
  - CreatedBy
  - Updated
  - UpdatedBy

## Inspections

- Inspections
- Inspections_Data

## Notes

- Notes
  - NoteID
  - NoteType
  - Notes
  - Created
  - CreatedBy
  - Updated
  - UpdatedBy
  - Deleted
  - DeletedBy
  - Locked
  - LockedBy
- Assets
  - AssetID
  - AssetType
  - NoteID

## Metadata

- Metadata_Users_Types
- Metadata_Location_Types
- Metadata_Hive_Types
- Metadata_Inspection_Types
- Metadata_Notes
  - NoteType
  - Desc
  - Created
  - CreatedBy
  - Updated
  - UpdatedBy
  - Enabled
