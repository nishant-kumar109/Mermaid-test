# 📐 Static Widgets - Detailed & Readable

This is a dedicated, spacious diagram showing the complete static widget system with proper spacing, clear blocks, and readable text.

## Overview
This diagram focuses exclusively on the static widget system with large, clear components and detailed descriptions for easy understanding.

## Static Widget System Diagram

```mermaid
graph TB
    %% Styling Definitions
    classDef responseClass fill:#e1f5fe,stroke:#01579b,stroke-width:4px,color:#000,font-weight:bold,font-size:16px
    classDef dataClass fill:#f3e5f5,stroke:#7b1fa2,stroke-width:3px,color:#000,font-weight:bold,font-size:15px
    classDef layoutClass fill:#e8f5e8,stroke:#2e7d32,stroke-width:3px,color:#000,font-weight:bold,font-size:14px
    classDef containerClass fill:#fff3e0,stroke:#ef6c00,stroke-width:2px,color:#000,font-size:13px
    classDef itemClass fill:#fce4ec,stroke:#c2185b,stroke-width:2px,color:#000,font-size:13px
    classDef componentClass fill:#f1f8e9,stroke:#558b2f,stroke-width:2px,color:#000,font-size:12px
    classDef propertyClass fill:#fafafa,stroke:#424242,stroke-width:1px,color:#000,font-size:11px
    
    %% Static Response - Top Level
    subgraph "🎯 STATIC RESPONSE LAYER"
        direction TB
        
        STATIC_RESPONSE["🎯 TicketResaleStaticInfoResponse<br/><b>Main Static API Response</b><br/>Complete response container for static widget data<br/>Contains all static layout and styling information"]
        
        STATIC_DATA["📊 StaticInfoData<br/><b>Core Static Data Container</b><br/>Main container for all static widget information<br/>Includes layouts, styles, and configurations"]
        
        RESPONSE_MESSAGE["💬 Message<br/><b>Response Status Messages</b><br/>Success, error, and status information<br/>User feedback and system messages"]
        
        RESPONSE_METADATA["📈 Metadata<br/><b>Analytics & Error Information</b><br/>Tracking data and error handling<br/>System monitoring and debugging"]
    end
    
    %% Static Data Structure - Second Level
    subgraph "📊 STATIC DATA STRUCTURE"
        direction TB
        
        META_INFO["📋 Meta<br/><b>Version Control Information</b><br/>Layout version and metadata<br/>System versioning and updates"]
        
        STYLES_SYSTEM["🎨 Styles<br/><b>CSS-like Styling System</b><br/>Visual styling definitions<br/>Theme and appearance control"]
        
        LAYOUTS_SYSTEM["📐 Layouts<br/><b>Layout Container System</b><br/>Main layout definitions<br/>UI structure and organization"]
        
        BOTTOMSHEETS_SYSTEM["📱 BottomSheets<br/><b>Modal Dialog System</b><br/>Modal dialogs and overlays<br/>User interaction modals"]
        
        STATIC_ACTIONS["⚡ StaticActions<br/><b>Predefined Action System</b><br/>Static action definitions<br/>System-level actions"]
    end
    
    %% Meta and Styling - Third Level
    subgraph "📋 META AND STYLING SYSTEM"
        direction TB
        
        VERSION_INFO["🔢 Version: int<br/><b>Layout Version Number</b><br/>Current version of the layout system<br/>Used for updates and compatibility"]
        
        STYLE_DEFINITIONS["📝 map[string]interface{}<br/><b>Style Definitions Map</b><br/>Key-value pairs for styling<br/>CSS-like property definitions"]
        
        ACTION_DEFINITIONS["📝 map[string]interface{}<br/><b>Action Definitions Map</b><br/>Key-value pairs for actions<br/>Predefined system actions"]
    end
    
    %% Layout System - Fourth Level
    subgraph "📐 LAYOUT SYSTEM"
        direction TB
        
        LAYOUT_CONTAINER["📐 Layout<br/><b>Main Layout Container</b><br/>Central layout management system<br/>Coordinates all layout components"]
        
        subgraph "🏗️ LAYOUT CONTAINERS"
            direction TB
            
            FOOTER_CONTAINER["🦶 TicketResaleFooterContainer<br/><b>Footer Layout Container</b><br/>Footer-specific layout definitions<br/>Bottom section layout control"]
            
            HEADER_CONTAINER["🎬 TicketResaleHeaderContainer<br/><b>Header Layout Container</b><br/>Header-specific layout definitions<br/>Top section layout control"]
            
            AMOUNT_CONTAINER["💰 AmountPaidContainer<br/><b>Payment Amount Layout</b><br/>Payment amount display layout<br/>Financial information presentation"]
            
            DETAILS_CONTAINER["📋 AmountDetailsContainer<br/><b>Payment Details Layout</b><br/>Payment details display layout<br/>Transaction information presentation"]
            
            FAQ_HEADER_CONTAINER["❓ FAQHeaderContainer<br/><b>FAQ Header Layout</b><br/>FAQ section header layout<br/>Question section organization"]
            
            FAQ_BODY_CONTAINER["📝 FAQBodyContainer<br/><b>FAQ Content Layout</b><br/>FAQ content display layout<br/>Answer section organization"]
            
            IMPORTANT_CONTAINER["⚠️ ImportantThingsToNoteContainer<br/><b>Important Notes Layout</b><br/>Important information layout<br/>Critical notice presentation"]
            
            REPLACE_CONTAINER["🔄 ReplaceTitleContainer<br/><b>Title Replacement Layout</b><br/>Dynamic title layout system<br/>Title modification control"]
            
            SEPARATOR_WIDGET["📊 SeparatorWidget<br/><b>Visual Separator</b><br/>Visual separation element<br/>UI section dividers"]
        end
    end
    
    %% Layout Items - Fifth Level
    subgraph "📄 LAYOUT ITEMS SYSTEM"
        direction TB
        
        MASTER_LAYOUT_ITEM["📄 MasterLayoutItem<br/><b>Base Layout Item</b><br/>Fundamental layout component<br/>Core layout building block"]
        
        PARENT_DATA_CONTAINER["📋 ParentData<br/><b>Parent Level Data Container</b><br/>Parent-level data management<br/>Top-level data organization"]
        
        CHILD_DATA_CONTAINER["📊 ChildData<br/><b>Child Level Data Container</b><br/>Child-level data management<br/>Nested data organization"]
        
        GRANDCHILD_DATA_CONTAINER["👶 GrandChildData<br/><b>Grandchild Level Data Container</b><br/>Grandchild-level data management<br/>Deeply nested data organization"]
    end
    
    %% Data Structure Details - Sixth Level
    subgraph "📊 DATA STRUCTURE DETAILS"
        direction TB
        
        subgraph "📋 PARENT DATA PROPERTIES"
            PARENT_TITLE["📝 Title: *GrandChildData<br/><b>Parent Item Title</b><br/>Title for parent-level items<br/>Main heading information"]
            
            PARENT_START_ACTIONS["⚡ StartActions: *[]StartActions<br/><b>Initialization Actions</b><br/>Actions performed at startup<br/>System initialization tasks"]
            
            PARENT_STYLE["🎨 Style: *StyleDetails<br/><b>Parent Styling Information</b><br/>Styling for parent-level items<br/>Visual appearance control"]
            
            PARENT_DATA["📊 Data: *ChildData<br/><b>Parent Data Container</b><br/>Data container for parent items<br/>Parent-level data storage"]
        end
        
        subgraph "📊 CHILD DATA PROPERTIES"
            CHILD_STYLE["🎨 Style: *StyleDetails<br/><b>Child Styling Information</b><br/>Styling for child-level items<br/>Visual appearance control"]
            
            CHILD_DATA_ARRAY["📊 Data: *[]GrandChildData<br/><b>Child Data Array</b><br/>Array of grandchild data items<br/>Multiple child items"]
            
            CHILD_TITLE["📝 Title: *GrandChildData<br/><b>Child Item Title</b><br/>Title for child-level items<br/>Sub-heading information"]
            
            CHILD_EXPANDED["📖 Expanded: *bool<br/><b>Expansion State</b><br/>Whether item is expanded<br/>Collapsible content control"]
            
            CHILD_CTA["🔘 CTA: *CTA<br/><b>Child Call to Action</b><br/>Action button for child items<br/>User interaction element"]
            
            CHILD_COMPONENTS["🧩 Components: *[]Component<br/><b>Child Components</b><br/>UI components for child items<br/>Visual elements"]
            
            CHILD_IMAGE["🖼️ Image: *EventImage<br/><b>Child Image</b><br/>Image for child items<br/>Visual content"]
        end
        
        subgraph "👶 GRANDCHILD DATA PROPERTIES"
            GRANDCHILD_STYLE_ID["🎨 StyleID: string<br/><b>Grandchild Style ID</b><br/>Style reference for grandchild items<br/>Styling identifier"]
            
            GRANDCHILD_COMPONENTS["🧩 Components: *[]Component<br/><b>Grandchild Components</b><br/>UI components for grandchild items<br/>Visual elements"]
            
            GRANDCHILD_TEXT_DETAIL["📝 TextDetail: *TextDetail<br/><b>Grandchild Text Content</b><br/>Text content for grandchild items<br/>Formatted text"]
            
            GRANDCHILD_CTA["🔘 CTA: *CTA<br/><b>Grandchild Call to Action</b><br/>Action button for grandchild items<br/>User interaction element"]
            
            GRANDCHILD_DATA_ARRAY["📊 Data: *[]GrandChildSupportData<br/><b>Grandchild Support Data</b><br/>Supporting data for grandchild items<br/>Additional information"]
            
            GRANDCHILD_STYLE["🎨 Style: *StyleDetails<br/><b>Grandchild Styling</b><br/>Styling for grandchild items<br/>Visual appearance control"]
            
            GRANDCHILD_LABEL["🏷️ Label: string<br/><b>Grandchild Label</b><br/>Label for grandchild items<br/>Identification text"]
        end
    end
    
    %% Components and Text - Seventh Level
    subgraph "🧩 COMPONENTS AND TEXT SYSTEM"
        direction TB
        
        COMPONENT_BLOCK["🧩 Component<br/><b>Basic Building Block</b><br/>Fundamental UI component<br/>Core visual element"]
        
        TEXT_DETAIL_BLOCK["📝 TextDetail<br/><b>Rich Text Content</b><br/>Formatted text with styling<br/>Text presentation system"]
        
        subgraph "🧩 COMPONENT PROPERTIES"
            COMPONENT_STYLE_ID["🎨 StyleID: string<br/><b>Component Style ID</b><br/>Style reference for component<br/>Styling identifier"]
            
            COMPONENT_TEXT["📝 Text: string<br/><b>Component Display Text</b><br/>Text content for component<br/>User-visible text"]
            
            COMPONENT_TYPE["🏷️ Type: string<br/><b>Component Type</b><br/>Type of component<br/>Component classification"]
            
            COMPONENT_VARS["🔗 Vars: *[]string<br/><b>Dynamic Variables</b><br/>Variables for component<br/>Dynamic content control"]
            
            COMPONENT_IMAGE_URL["🖼️ ImageURL: string<br/><b>Component Image Source</b><br/>Image source for component<br/>Visual content URL"]
        end
        
        subgraph "📝 TEXT DETAIL PROPERTIES"
            TEXT_DETAIL_COMPONENTS["🧩 Components: []Component<br/><b>Text Detail Components</b><br/>Components within text detail<br/>Nested components"]
            
            TEXT_DETAIL_STYLE_ID["🎨 StyleID: string<br/><b>Text Detail Style ID</b><br/>Style reference for text detail<br/>Text styling identifier"]
        end
    end
    
    %% Bottom Sheets System - Eighth Level
    subgraph "📱 BOTTOM SHEETS SYSTEM"
        direction TB
        
        BOTTOMSHEETS_CONTAINER["📱 BottomSheets<br/><b>Modal Dialog System</b><br/>Complete modal dialog framework<br/>User interaction modals"]
        
        CONFIRMATION_DIALOG["✅ Confirmation<br/><b>Confirmation Dialog</b><br/>User confirmation modals<br/>Decision-making interface"]
        
        subgraph "🎨 MODAL COMPONENTS"
            BOTTOMSHEET_WIDGET["🎨 BottomSheetWidget<br/><b>Modal Widget</b><br/>Widget within modal dialog<br/>Modal content element"]
            
            BOTTOMSHEET_CTA_DATA["🔘 BottomSheetCtaData<br/><b>Modal CTA Data</b><br/>Call-to-action data for modal<br/>Modal interaction element"]
            
            BOTTOMSHEET_CTA["🔘 BottomSheetCTA<br/><b>Modal Call to Action</b><br/>Interactive element in modal<br/>User action button"]
        end
        
        subgraph "🖼️ MODAL ELEMENTS"
            LEFT_ICON["🖼️ LeftIcon<br/><b>Widget Icon</b><br/>Icon for modal widgets<br/>Visual indicator"]
            
            BOTTOMSHEET_TEXT["📝 BottomSheetText<br/><b>Widget Text</b><br/>Text content in modal<br/>Modal text content"]
        end
        
        subgraph "📊 MODAL ANALYTICS"
            STATIC_ANALYTICS["📊 StaticAnalyticsData<br/><b>Modal Analytics</b><br/>Analytics for modal interactions<br/>User behavior tracking"]
        end
    end
    
    %% CTA System - Ninth Level
    subgraph "🔘 CTA SYSTEM"
        direction TB
        
        CTA_BLOCK["🔘 CTA<br/><b>Call to Action</b><br/>Interactive button or link<br/>User interaction element"]
        
        subgraph "🔘 CTA PROPERTIES"
            CTA_LABEL["🏷️ Label: string<br/><b>CTA Button Text</b><br/>Text displayed on button<br/>User-visible label"]
            
            CTA_URL["🌐 URL: string<br/><b>CTA Destination URL</b><br/>Link destination<br/>Navigation target"]
            
            CTA_TYPE["🏷️ Type: string<br/><b>CTA Action Type</b><br/>Type of action performed<br/>Action classification"]
            
            CTA_ID["🆔 ID: string<br/><b>CTA Unique Identifier</b><br/>Unique ID for CTA<br/>Element identification"]
            
            CTA_ADDITIONAL_DATA["📋 AdditionalData: *CtaAdditionalData<br/><b>CTA Additional Data</b><br/>Extra data for CTA<br/>Additional configuration"]
            
            CTA_ANALYTICS["📊 Analytics: *Analytics<br/><b>CTA Analytics</b><br/>Analytics for CTA interactions<br/>User behavior tracking"]
        end
        
        subgraph "📋 CTA ADDITIONAL DATA"
            CTA_ADDITIONAL_REPLACE["🔄 ReplaceTitleLayout: string<br/><b>Title Replacement Layout</b><br/>Layout for title replacement<br/>Dynamic title control"]
            
            CTA_ADDITIONAL_ID["🆔 CtaId: string<br/><b>CTA ID</b><br/>CTA identifier<br/>Element reference"]
        end
    end
    
    %% Analytics System - Tenth Level
    subgraph "📊 ANALYTICS SYSTEM"
        direction TB
        
        ANALYTICS_BLOCK["📊 Analytics<br/><b>Dynamic Analytics</b><br/>User behavior tracking<br/>System monitoring"]
        
        subgraph "📊 ANALYTICS PROPERTIES"
            ANALYTICS_PRODUCT["📱 Product: string<br/><b>Product Name</b><br/>Product being tracked<br/>Application identifier"]
            
            ANALYTICS_SCREEN["📺 ScreenName: string<br/><b>Screen Name</b><br/>Current screen being viewed<br/>Page identifier"]
            
            ANALYTICS_TITLE["🏷️ Title: string<br/><b>Event Title</b><br/>Title of the event<br/>Event identification"]
            
            ANALYTICS_VENUE["🏢 VenueCode: string<br/><b>Venue Code</b><br/>Venue identifier<br/>Location tracking"]
            
            ANALYTICS_METADATA["📊 Metadata: string<br/><b>Additional Metadata</b><br/>Extra tracking information<br/>Context data"]
            
            ANALYTICS_CATEGORY["📂 Category: string<br/><b>Event Category</b><br/>Category of the event<br/>Event classification"]
            
            ANALYTICS_SUBCATEGORY["📂 SubCategory: string<br/><b>Event Subcategory</b><br/>Subcategory of the event<br/>Detailed classification"]
            
            ANALYTICS_EVENT_NAME["🎭 EventName: string<br/><b>Event Name</b><br/>Name of the event<br/>Event identification"]
            
            ANALYTICS_EVENT_TYPE["🏷️ EventType: string<br/><b>Event Type</b><br/>Type of the event<br/>Event classification"]
            
            ANALYTICS_EVENT_CODE["🆔 EventCode: string<br/><b>Event Code</b><br/>Code for the event<br/>Event reference"]
            
            ANALYTICS_EVENT_GROUP["👥 EventGroup: string<br/><b>Event Group</b><br/>Group the event belongs to<br/>Event organization"]
            
            ANALYTICS_GENRE["🎨 Genre: string<br/><b>Event Genre</b><br/>Genre of the event<br/>Event category"]
            
            ANALYTICS_SUBGENRE["🎨 SubGenre: string<br/><b>Event Subgenre</b><br/>Subgenre of the event<br/>Detailed genre"]
            
            ANALYTICS_LANGUAGE["🗣️ Language: string<br/><b>Event Language</b><br/>Language of the event<br/>Localization"]
            
            ANALYTICS_PRICE["💰 Price: string<br/><b>Event Price</b><br/>Price of the event<br/>Cost information"]
            
            ANALYTICS_TRANSACTION_ID["🆔 TransactionID: string<br/><b>Transaction ID</b><br/>Transaction identifier<br/>Payment tracking"]
            
            ANALYTICS_IS_TVOD["📺 IsTvod: string<br/><b>Is TVOD</b><br/>TVOD status<br/>Content type"]
        end
    end
    
    %% Footer Structure - Eleventh Level
    subgraph "🦶 FOOTER STRUCTURE"
        direction TB
        
        FOOTER_ITEM_DATA["🦶 TicketResaleFooterItemData<br/><b>Footer Item Data</b><br/>Data for footer items<br/>Footer content container"]
        
        subgraph "🦶 FOOTER PROPERTIES"
            FOOTER_TYPE["🏷️ Type: string<br/><b>Footer Type</b><br/>Type of footer item<br/>Footer classification"]
            
            FOOTER_STYLE_ID["🎨 StyleID: string<br/><b>Footer Style ID</b><br/>Style reference for footer<br/>Footer styling"]
            
            FOOTER_DATA["📋 Data: FooterParentData<br/><b>Footer Parent Data</b><br/>Parent data for footer<br/>Footer data container"]
        end
        
        FOOTER_PARENT_DATA["📋 FooterParentData<br/><b>Footer Parent Container</b><br/>Parent container for footer<br/>Footer data organization"]
        
        FOOTER_CHILD_DATA["📄 FooterChildData<br/><b>Footer Child Data</b><br/>Child data for footer<br/>Footer item details"]
        
        subgraph "📄 FOOTER CHILD PROPERTIES"
            FOOTER_CHILD_LABEL["🏷️ Label: string<br/><b>Footer Label</b><br/>Label for footer item<br/>Footer identification"]
            
            FOOTER_CHILD_TEXT["📝 Text: []TextDetail<br/><b>Footer Text</b><br/>Text content for footer<br/>Footer text content"]
            
            FOOTER_CHILD_CTA["🔘 CTA: *CTA<br/><b>Footer CTA</b><br/>Call-to-action for footer<br/>Footer interaction"]
        end
    end
    
    %% Start Actions - Twelfth Level
    subgraph "⚡ START ACTIONS"
        direction TB
        
        START_ACTIONS["⚡ StartActions<br/><b>Initialization Actions</b><br/>Actions performed at startup<br/>System initialization"]
        
        subgraph "⚡ START ACTION PROPERTIES"
            START_ACTION_ICON["🖼️ IconUrl: string<br/><b>Action Icon URL</b><br/>URL for action icon<br/>Visual indicator"]
            
            START_ACTION_CTA["🔘 CTA: *CTA<br/><b>Action CTA</b><br/>Call-to-action for start action<br/>User interaction"]
        end
    end
    
    %% Style Details - Thirteenth Level
    subgraph "🎨 STYLE DETAILS"
        direction TB
        
        STYLE_DETAILS["🎨 StyleDetails<br/><b>Styling Information</b><br/>Visual styling data<br/>Appearance control"]
        
        STYLE_AXIS["📐 Axis: string<br/><b>Layout Axis</b><br/>Layout direction control<br/>Orientation setting"]
    end
    
    %% Main Connections
    STATIC_RESPONSE --> STATIC_DATA
    STATIC_RESPONSE --> RESPONSE_MESSAGE
    STATIC_RESPONSE --> RESPONSE_METADATA
    
    STATIC_DATA --> META_INFO
    STATIC_DATA --> STYLES_SYSTEM
    STATIC_DATA --> LAYOUTS_SYSTEM
    STATIC_DATA --> BOTTOMSHEETS_SYSTEM
    STATIC_DATA --> STATIC_ACTIONS
    
    META_INFO --> VERSION_INFO
    STYLES_SYSTEM --> STYLE_DEFINITIONS
    STATIC_ACTIONS --> ACTION_DEFINITIONS
    
    LAYOUTS_SYSTEM --> LAYOUT_CONTAINER
    LAYOUT_CONTAINER --> FOOTER_CONTAINER
    LAYOUT_CONTAINER --> HEADER_CONTAINER
    LAYOUT_CONTAINER --> AMOUNT_CONTAINER
    LAYOUT_CONTAINER --> DETAILS_CONTAINER
    LAYOUT_CONTAINER --> FAQ_HEADER_CONTAINER
    LAYOUT_CONTAINER --> FAQ_BODY_CONTAINER
    LAYOUT_CONTAINER --> IMPORTANT_CONTAINER
    LAYOUT_CONTAINER --> REPLACE_CONTAINER
    LAYOUT_CONTAINER --> SEPARATOR_WIDGET
    
    LAYOUT_CONTAINER --> MASTER_LAYOUT_ITEM
    MASTER_LAYOUT_ITEM --> PARENT_DATA_CONTAINER
    PARENT_DATA_CONTAINER --> CHILD_DATA_CONTAINER
    CHILD_DATA_CONTAINER --> GRANDCHILD_DATA_CONTAINER
    
    PARENT_DATA_CONTAINER --> PARENT_TITLE
    PARENT_DATA_CONTAINER --> PARENT_START_ACTIONS
    PARENT_DATA_CONTAINER --> PARENT_STYLE
    PARENT_DATA_CONTAINER --> PARENT_DATA
    
    CHILD_DATA_CONTAINER --> CHILD_STYLE
    CHILD_DATA_CONTAINER --> CHILD_DATA_ARRAY
    CHILD_DATA_CONTAINER --> CHILD_TITLE
    CHILD_DATA_CONTAINER --> CHILD_EXPANDED
    CHILD_DATA_CONTAINER --> CHILD_CTA
    CHILD_DATA_CONTAINER --> CHILD_COMPONENTS
    CHILD_DATA_CONTAINER --> CHILD_IMAGE
    
    GRANDCHILD_DATA_CONTAINER --> GRANDCHILD_STYLE_ID
    GRANDCHILD_DATA_CONTAINER --> GRANDCHILD_COMPONENTS
    GRANDCHILD_DATA_CONTAINER --> GRANDCHILD_TEXT_DETAIL
    GRANDCHILD_DATA_CONTAINER --> GRANDCHILD_CTA
    GRANDCHILD_DATA_CONTAINER --> GRANDCHILD_DATA_ARRAY
    GRANDCHILD_DATA_CONTAINER --> GRANDCHILD_STYLE
    GRANDCHILD_DATA_CONTAINER --> GRANDCHILD_LABEL
    
    GRANDCHILD_COMPONENTS --> COMPONENT_BLOCK
    CHILD_COMPONENTS --> COMPONENT_BLOCK
    GRANDCHILD_TEXT_DETAIL --> TEXT_DETAIL_BLOCK
    TEXT_DETAIL_BLOCK --> COMPONENT_BLOCK
    
    COMPONENT_BLOCK --> COMPONENT_STYLE_ID
    COMPONENT_BLOCK --> COMPONENT_TEXT
    COMPONENT_BLOCK --> COMPONENT_TYPE
    COMPONENT_BLOCK --> COMPONENT_VARS
    COMPONENT_BLOCK --> COMPONENT_IMAGE_URL
    
    TEXT_DETAIL_BLOCK --> TEXT_DETAIL_COMPONENTS
    TEXT_DETAIL_BLOCK --> TEXT_DETAIL_STYLE_ID
    
    BOTTOMSHEETS_SYSTEM --> BOTTOMSHEETS_CONTAINER
    BOTTOMSHEETS_CONTAINER --> CONFIRMATION_DIALOG
    CONFIRMATION_DIALOG --> BOTTOMSHEET_WIDGET
    CONFIRMATION_DIALOG --> BOTTOMSHEET_CTA_DATA
    CONFIRMATION_DIALOG --> STATIC_ANALYTICS
    BOTTOMSHEET_CTA_DATA --> BOTTOMSHEET_CTA
    BOTTOMSHEET_WIDGET --> LEFT_ICON
    BOTTOMSHEET_WIDGET --> BOTTOMSHEET_TEXT
    
    CHILD_CTA --> CTA_BLOCK
    GRANDCHILD_CTA --> CTA_BLOCK
    FOOTER_CHILD_CTA --> CTA_BLOCK
    START_ACTION_CTA --> CTA_BLOCK
    
    CTA_BLOCK --> CTA_LABEL
    CTA_BLOCK --> CTA_URL
    CTA_BLOCK --> CTA_TYPE
    CTA_BLOCK --> CTA_ID
    CTA_BLOCK --> CTA_ADDITIONAL_DATA
    CTA_BLOCK --> CTA_ANALYTICS
    
    CTA_ADDITIONAL_DATA --> CTA_ADDITIONAL_REPLACE
    CTA_ADDITIONAL_DATA --> CTA_ADDITIONAL_ID
    
    CTA_ANALYTICS --> ANALYTICS_BLOCK
    STATIC_ANALYTICS --> ANALYTICS_BLOCK
    
    ANALYTICS_BLOCK --> ANALYTICS_PRODUCT
    ANALYTICS_BLOCK --> ANALYTICS_SCREEN
    ANALYTICS_BLOCK --> ANALYTICS_TITLE
    ANALYTICS_BLOCK --> ANALYTICS_VENUE
    ANALYTICS_BLOCK --> ANALYTICS_METADATA
    ANALYTICS_BLOCK --> ANALYTICS_CATEGORY
    ANALYTICS_BLOCK --> ANALYTICS_SUBCATEGORY
    ANALYTICS_BLOCK --> ANALYTICS_EVENT_NAME
    ANALYTICS_BLOCK --> ANALYTICS_EVENT_TYPE
    ANALYTICS_BLOCK --> ANALYTICS_EVENT_CODE
    ANALYTICS_BLOCK --> ANALYTICS_EVENT_GROUP
    ANALYTICS_BLOCK --> ANALYTICS_GENRE
    ANALYTICS_BLOCK --> ANALYTICS_SUBGENRE
    ANALYTICS_BLOCK --> ANALYTICS_LANGUAGE
    ANALYTICS_BLOCK --> ANALYTICS_PRICE
    ANALYTICS_BLOCK --> ANALYTICS_TRANSACTION_ID
    ANALYTICS_BLOCK --> ANALYTICS_IS_TVOD
    
    LAYOUT_CONTAINER --> FOOTER_ITEM_DATA
    FOOTER_ITEM_DATA --> FOOTER_TYPE
    FOOTER_ITEM_DATA --> FOOTER_STYLE_ID
    FOOTER_ITEM_DATA --> FOOTER_DATA
    FOOTER_DATA --> FOOTER_PARENT_DATA
    FOOTER_PARENT_DATA --> FOOTER_CHILD_DATA
    FOOTER_CHILD_DATA --> FOOTER_CHILD_LABEL
    FOOTER_CHILD_DATA --> FOOTER_CHILD_TEXT
    FOOTER_CHILD_DATA --> FOOTER_CHILD_CTA
    
    PARENT_START_ACTIONS --> START_ACTIONS
    START_ACTIONS --> START_ACTION_ICON
    START_ACTIONS --> START_ACTION_CTA
    
    CHILD_STYLE --> STYLE_DETAILS
    GRANDCHILD_STYLE --> STYLE_DETAILS
    PARENT_STYLE --> STYLE_DETAILS
    STYLE_DETAILS --> STYLE_AXIS
    
    %% Apply Styling Classes
    class STATIC_RESPONSE,STATIC_DATA,RESPONSE_MESSAGE,RESPONSE_METADATA responseClass
    class META_INFO,STYLES_SYSTEM,LAYOUTS_SYSTEM,BOTTOMSHEETS_SYSTEM,STATIC_ACTIONS dataClass
    class VERSION_INFO,STYLE_DEFINITIONS,ACTION_DEFINITIONS propertyClass
    class LAYOUT_CONTAINER,FOOTER_CONTAINER,HEADER_CONTAINER,AMOUNT_CONTAINER,DETAILS_CONTAINER,FAQ_HEADER_CONTAINER,FAQ_BODY_CONTAINER,IMPORTANT_CONTAINER,REPLACE_CONTAINER,SEPARATOR_WIDGET layoutClass
    class MASTER_LAYOUT_ITEM,PARENT_DATA_CONTAINER,CHILD_DATA_CONTAINER,GRANDCHILD_DATA_CONTAINER containerClass
    class PARENT_TITLE,PARENT_START_ACTIONS,PARENT_STYLE,PARENT_DATA,CHILD_STYLE,CHILD_DATA_ARRAY,CHILD_TITLE,CHILD_EXPANDED,CHILD_CTA,CHILD_COMPONENTS,CHILD_IMAGE,GRANDCHILD_STYLE_ID,GRANDCHILD_COMPONENTS,GRANDCHILD_TEXT_DETAIL,GRANDCHILD_CTA,GRANDCHILD_DATA_ARRAY,GRANDCHILD_STYLE,GRANDCHILD_LABEL itemClass
    class COMPONENT_BLOCK,TEXT_DETAIL_BLOCK,COMPONENT_STYLE_ID,COMPONENT_TEXT,COMPONENT_TYPE,COMPONENT_VARS,COMPONENT_IMAGE_URL,TEXT_DETAIL_COMPONENTS,TEXT_DETAIL_STYLE_ID componentClass
    class BOTTOMSHEETS_CONTAINER,CONFIRMATION_DIALOG,BOTTOMSHEET_WIDGET,BOTTOMSHEET_CTA_DATA,BOTTOMSHEET_CTA,LEFT_ICON,BOTTOMSHEET_TEXT,STATIC_ANALYTICS containerClass
    class CTA_BLOCK,CTA_LABEL,CTA_URL,CTA_TYPE,CTA_ID,CTA_ADDITIONAL_DATA,CTA_ANALYTICS,CTA_ADDITIONAL_REPLACE,CTA_ADDITIONAL_ID componentClass
    class ANALYTICS_BLOCK,ANALYTICS_PRODUCT,ANALYTICS_SCREEN,ANALYTICS_TITLE,ANALYTICS_VENUE,ANALYTICS_METADATA,ANALYTICS_CATEGORY,ANALYTICS_SUBCATEGORY,ANALYTICS_EVENT_NAME,ANALYTICS_EVENT_TYPE,ANALYTICS_EVENT_CODE,ANALYTICS_EVENT_GROUP,ANALYTICS_GENRE,ANALYTICS_SUBGENRE,ANALYTICS_LANGUAGE,ANALYTICS_PRICE,ANALYTICS_TRANSACTION_ID,ANALYTICS_IS_TVOD componentClass
    class FOOTER_ITEM_DATA,FOOTER_TYPE,FOOTER_STYLE_ID,FOOTER_DATA,FOOTER_PARENT_DATA,FOOTER_CHILD_DATA,FOOTER_CHILD_LABEL,FOOTER_CHILD_TEXT,FOOTER_CHILD_CTA containerClass
    class START_ACTIONS,START_ACTION_ICON,START_ACTION_CTA componentClass
    class STYLE_DETAILS,STYLE_AXIS propertyClass
```

## Static Widget System Overview

### 🎯 **STATIC RESPONSE LAYER**
- **TicketResaleStaticInfoResponse**: Main API response container
- **StaticInfoData**: Core static data container
- **Message**: Response status and feedback
- **Metadata**: Analytics and error handling

### 📊 **STATIC DATA STRUCTURE**
- **Meta**: Version control and system metadata
- **Styles**: CSS-like styling system
- **Layouts**: Layout container system
- **BottomSheets**: Modal dialog system
- **StaticActions**: Predefined action system

### 📋 **META AND STYLING SYSTEM**
- **Version**: Layout version control
- **Style Definitions**: Key-value styling pairs
- **Action Definitions**: Predefined system actions

### 📐 **LAYOUT SYSTEM**
- **Layout Container**: Main layout management
- **Layout Containers**: Specific UI section layouts
- **Layout Items**: Hierarchical data structure

### 📄 **LAYOUT ITEMS SYSTEM**
- **MasterLayoutItem**: Base layout component
- **ParentData**: Parent-level data container
- **ChildData**: Child-level data container
- **GrandChildData**: Grandchild-level data container

### 📊 **DATA STRUCTURE DETAILS**
- **Parent Data Properties**: Title, actions, style, data
- **Child Data Properties**: Style, data array, title, expansion, CTA, components, image
- **GrandChild Data Properties**: Style ID, components, text detail, CTA, data array, style, label

### 🧩 **COMPONENTS AND TEXT SYSTEM**
- **Component**: Basic UI building block
- **TextDetail**: Rich text content
- **Component Properties**: Style ID, text, type, variables, image URL
- **Text Detail Properties**: Components, style ID

### 📱 **BOTTOM SHEETS SYSTEM**
- **BottomSheets**: Modal dialog framework
- **Confirmation**: User confirmation modals
- **Modal Components**: Widgets, CTAs, icons, text
- **Modal Analytics**: User behavior tracking

### 🔘 **CTA SYSTEM**
- **CTA**: Call-to-action buttons and links
- **CTA Properties**: Label, URL, type, ID, additional data, analytics
- **CTA Additional Data**: Title replacement, CTA ID

### 📊 **ANALYTICS SYSTEM**
- **Analytics**: Comprehensive user behavior tracking
- **Analytics Properties**: Product, screen, title, venue, metadata, category, event details, price, transaction

### 🦶 **FOOTER STRUCTURE**
- **Footer Item Data**: Footer content container
- **Footer Properties**: Type, style ID, data
- **Footer Parent/Child Data**: Hierarchical footer organization

### ⚡ **START ACTIONS**
- **StartActions**: System initialization actions
- **Start Action Properties**: Icon URL, CTA

### 🎨 **STYLE DETAILS**
- **StyleDetails**: Visual styling information
- **Style Properties**: Layout axis control

## Key Features

### 🎯 **Spacious Design**
- **Large Blocks**: Each component has plenty of space
- **Clear Text**: Readable text with proper sizing
- **Visual Separation**: Clear boundaries between sections
- **Proper Branching**: Clear connection lines and relationships

### 🎨 **Professional Styling**
- **Color Coding**: Different colors for different system layers
- **Font Sizing**: Appropriate font sizes for readability
- **Stroke Weights**: Different weights for importance levels
- **High Contrast**: Excellent readability

### 📊 **Comprehensive Coverage**
- **Complete System**: All static widget components
- **Detailed Information**: Full property and configuration details
- **Clear Hierarchy**: Visual hierarchy with proper spacing
- **Easy Navigation**: Logical flow and organization

## Usage
- **Static System Understanding**: Complete static widget architecture
- **Development Reference**: Implementation guidance for static widgets
- **Documentation**: Comprehensive static system documentation
- **Presentations**: Professional static widget diagrams
- **Team Collaboration**: Shared understanding of static system structure
