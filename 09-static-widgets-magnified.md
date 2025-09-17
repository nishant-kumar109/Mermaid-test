# 📐 Static Widgets - MAGNIFIED & ULTRA-READABLE

This is a **MAGNIFIED** version of the static widget diagram with **MASSIVE** text, **HUGE** blocks, and **MAXIMUM** spacing for ultimate readability.

## Overview
This diagram is **EXTREMELY LARGE** with **GIANT** text and **MASSIVE** spacing for presentations, large screens, and maximum clarity.

## MAGNIFIED Static Widget System Diagram

```mermaid
graph TB
    %% ULTRA-LARGE Styling Definitions
    classDef responseClass fill:#e1f5fe,stroke:#01579b,stroke-width:8px,color:#000,font-weight:bold,font-size:24px
    classDef dataClass fill:#f3e5f5,stroke:#7b1fa2,stroke-width:6px,color:#000,font-weight:bold,font-size:22px
    classDef layoutClass fill:#e8f5e8,stroke:#2e7d32,stroke-width:5px,color:#000,font-weight:bold,font-size:20px
    classDef containerClass fill:#fff3e0,stroke:#ef6c00,stroke-width:4px,color:#000,font-size:18px
    classDef itemClass fill:#fce4ec,stroke:#c2185b,stroke-width:3px,color:#000,font-size:16px
    classDef componentClass fill:#f1f8e9,stroke:#558b2f,stroke-width:3px,color:#000,font-size:14px
    classDef propertyClass fill:#fafafa,stroke:#424242,stroke-width:2px,color:#000,font-size:12px
    
    %% MASSIVE Static Response - Top Level
    subgraph "🎯 MASSIVE STATIC RESPONSE LAYER"
        direction TB
        
        STATIC_RESPONSE["🎯 TicketResaleStaticInfoResponse<br/><b>MAIN STATIC API RESPONSE</b><br/>Complete response container for static widget data<br/>Contains all static layout and styling information<br/>Primary entry point for static widget system"]
        
        STATIC_DATA["📊 StaticInfoData<br/><b>CORE STATIC DATA CONTAINER</b><br/>Main container for all static widget information<br/>Includes layouts, styles, and configurations<br/>Central data management system"]
        
        RESPONSE_MESSAGE["💬 Message<br/><b>RESPONSE STATUS MESSAGES</b><br/>Success, error, and status information<br/>User feedback and system messages<br/>Communication layer"]
        
        RESPONSE_METADATA["📈 Metadata<br/><b>ANALYTICS & ERROR INFORMATION</b><br/>Tracking data and error handling<br/>System monitoring and debugging<br/>Performance metrics"]
    end
    
    %% HUGE Static Data Structure - Second Level
    subgraph "📊 HUGE STATIC DATA STRUCTURE"
        direction TB
        
        META_INFO["📋 Meta<br/><b>VERSION CONTROL INFORMATION</b><br/>Layout version and metadata<br/>System versioning and updates<br/>Configuration management"]
        
        STYLES_SYSTEM["🎨 Styles<br/><b>CSS-LIKE STYLING SYSTEM</b><br/>Visual styling definitions<br/>Theme and appearance control<br/>Design system management"]
        
        LAYOUTS_SYSTEM["📐 Layouts<br/><b>LAYOUT CONTAINER SYSTEM</b><br/>Main layout definitions<br/>UI structure and organization<br/>Page layout management"]
        
        BOTTOMSHEETS_SYSTEM["📱 BottomSheets<br/><b>MODAL DIALOG SYSTEM</b><br/>Modal dialogs and overlays<br/>User interaction modals<br/>Dialog management system"]
        
        STATIC_ACTIONS["⚡ StaticActions<br/><b>PREDEFINED ACTION SYSTEM</b><br/>Static action definitions<br/>System-level actions<br/>Action management framework"]
    end
    
    %% LARGE Meta and Styling - Third Level
    subgraph "📋 LARGE META AND STYLING SYSTEM"
        direction TB
        
        VERSION_INFO["🔢 Version: int<br/><b>LAYOUT VERSION NUMBER</b><br/>Current version of the layout system<br/>Used for updates and compatibility<br/>Version control mechanism"]
        
        STYLE_DEFINITIONS["📝 map[string]interface{}<br/><b>STYLE DEFINITIONS MAP</b><br/>Key-value pairs for styling<br/>CSS-like property definitions<br/>Style configuration storage"]
        
        ACTION_DEFINITIONS["📝 map[string]interface{}<br/><b>ACTION DEFINITIONS MAP</b><br/>Key-value pairs for actions<br/>Predefined system actions<br/>Action configuration storage"]
    end
    
    %% MASSIVE Layout System - Fourth Level
    subgraph "📐 MASSIVE LAYOUT SYSTEM"
        direction TB
        
        LAYOUT_CONTAINER["📐 Layout<br/><b>MAIN LAYOUT CONTAINER</b><br/>Central layout management system<br/>Coordinates all layout components<br/>Primary layout controller"]
        
        subgraph "🏗️ MASSIVE LAYOUT CONTAINERS"
            direction TB
            
            FOOTER_CONTAINER["🦶 TicketResaleFooterContainer<br/><b>FOOTER LAYOUT CONTAINER</b><br/>Footer-specific layout definitions<br/>Bottom section layout control<br/>Footer management system"]
            
            HEADER_CONTAINER["🎬 TicketResaleHeaderContainer<br/><b>HEADER LAYOUT CONTAINER</b><br/>Header-specific layout definitions<br/>Top section layout control<br/>Header management system"]
            
            AMOUNT_CONTAINER["💰 AmountPaidContainer<br/><b>PAYMENT AMOUNT LAYOUT</b><br/>Payment amount display layout<br/>Financial information presentation<br/>Amount display system"]
            
            DETAILS_CONTAINER["📋 AmountDetailsContainer<br/><b>PAYMENT DETAILS LAYOUT</b><br/>Payment details display layout<br/>Transaction information presentation<br/>Details display system"]
            
            FAQ_HEADER_CONTAINER["❓ FAQHeaderContainer<br/><b>FAQ HEADER LAYOUT</b><br/>FAQ section header layout<br/>Question section organization<br/>FAQ header management"]
            
            FAQ_BODY_CONTAINER["📝 FAQBodyContainer<br/><b>FAQ CONTENT LAYOUT</b><br/>FAQ content display layout<br/>Answer section organization<br/>FAQ content management"]
            
            IMPORTANT_CONTAINER["⚠️ ImportantThingsToNoteContainer<br/><b>IMPORTANT NOTES LAYOUT</b><br/>Important information layout<br/>Critical notice presentation<br/>Important info management"]
            
            REPLACE_CONTAINER["🔄 ReplaceTitleContainer<br/><b>TITLE REPLACEMENT LAYOUT</b><br/>Dynamic title layout system<br/>Title modification control<br/>Title management system"]
            
            SEPARATOR_WIDGET["📊 SeparatorWidget<br/><b>VISUAL SEPARATOR</b><br/>Visual separation element<br/>UI section dividers<br/>Layout separation system"]
        end
    end
    
    %% HUGE Layout Items - Fifth Level
    subgraph "📄 HUGE LAYOUT ITEMS SYSTEM"
        direction TB
        
        MASTER_LAYOUT_ITEM["📄 MasterLayoutItem<br/><b>BASE LAYOUT ITEM</b><br/>Fundamental layout component<br/>Core layout building block<br/>Primary layout element"]
        
        PARENT_DATA_CONTAINER["📋 ParentData<br/><b>PARENT LEVEL DATA CONTAINER</b><br/>Parent-level data management<br/>Top-level data organization<br/>Parent data system"]
        
        CHILD_DATA_CONTAINER["📊 ChildData<br/><b>CHILD LEVEL DATA CONTAINER</b><br/>Child-level data management<br/>Nested data organization<br/>Child data system"]
        
        GRANDCHILD_DATA_CONTAINER["👶 GrandChildData<br/><b>GRANDCHILD LEVEL DATA CONTAINER</b><br/>Grandchild-level data management<br/>Deeply nested data organization<br/>Grandchild data system"]
    end
    
    %% MASSIVE Data Structure Details - Sixth Level
    subgraph "📊 MASSIVE DATA STRUCTURE DETAILS"
        direction TB
        
        subgraph "📋 HUGE PARENT DATA PROPERTIES"
            PARENT_TITLE["📝 Title: *GrandChildData<br/><b>PARENT ITEM TITLE</b><br/>Title for parent-level items<br/>Main heading information<br/>Parent title system"]
            
            PARENT_START_ACTIONS["⚡ StartActions: *[]StartActions<br/><b>INITIALIZATION ACTIONS</b><br/>Actions performed at startup<br/>System initialization tasks<br/>Startup action system"]
            
            PARENT_STYLE["🎨 Style: *StyleDetails<br/><b>PARENT STYLING INFORMATION</b><br/>Styling for parent-level items<br/>Visual appearance control<br/>Parent style system"]
            
            PARENT_DATA["📊 Data: *ChildData<br/><b>PARENT DATA CONTAINER</b><br/>Data container for parent items<br/>Parent-level data storage<br/>Parent data management"]
        end
        
        subgraph "📊 HUGE CHILD DATA PROPERTIES"
            CHILD_STYLE["🎨 Style: *StyleDetails<br/><b>CHILD STYLING INFORMATION</b><br/>Styling for child-level items<br/>Visual appearance control<br/>Child style system"]
            
            CHILD_DATA_ARRAY["📊 Data: *[]GrandChildData<br/><b>CHILD DATA ARRAY</b><br/>Array of grandchild data items<br/>Multiple child items<br/>Child data collection"]
            
            CHILD_TITLE["📝 Title: *GrandChildData<br/><b>CHILD ITEM TITLE</b><br/>Title for child-level items<br/>Sub-heading information<br/>Child title system"]
            
            CHILD_EXPANDED["📖 Expanded: *bool<br/><b>EXPANSION STATE</b><br/>Whether item is expanded<br/>Collapsible content control<br/>Expansion management"]
            
            CHILD_CTA["🔘 CTA: *CTA<br/><b>CHILD CALL TO ACTION</b><br/>Action button for child items<br/>User interaction element<br/>Child action system"]
            
            CHILD_COMPONENTS["🧩 Components: *[]Component<br/><b>CHILD COMPONENTS</b><br/>UI components for child items<br/>Visual elements<br/>Child component system"]
            
            CHILD_IMAGE["🖼️ Image: *EventImage<br/><b>CHILD IMAGE</b><br/>Image for child items<br/>Visual content<br/>Child image system"]
        end
        
        subgraph "👶 HUGE GRANDCHILD DATA PROPERTIES"
            GRANDCHILD_STYLE_ID["🎨 StyleID: string<br/><b>GRANDCHILD STYLE ID</b><br/>Style reference for grandchild items<br/>Styling identifier<br/>Grandchild style reference"]
            
            GRANDCHILD_COMPONENTS["🧩 Components: *[]Component<br/><b>GRANDCHILD COMPONENTS</b><br/>UI components for grandchild items<br/>Visual elements<br/>Grandchild component system"]
            
            GRANDCHILD_TEXT_DETAIL["📝 TextDetail: *TextDetail<br/><b>GRANDCHILD TEXT CONTENT</b><br/>Text content for grandchild items<br/>Formatted text<br/>Grandchild text system"]
            
            GRANDCHILD_CTA["🔘 CTA: *CTA<br/><b>GRANDCHILD CALL TO ACTION</b><br/>Action button for grandchild items<br/>User interaction element<br/>Grandchild action system"]
            
            GRANDCHILD_DATA_ARRAY["📊 Data: *[]GrandChildSupportData<br/><b>GRANDCHILD SUPPORT DATA</b><br/>Supporting data for grandchild items<br/>Additional information<br/>Grandchild support system"]
            
            GRANDCHILD_STYLE["🎨 Style: *StyleDetails<br/><b>GRANDCHILD STYLING</b><br/>Styling for grandchild items<br/>Visual appearance control<br/>Grandchild style system"]
            
            GRANDCHILD_LABEL["🏷️ Label: string<br/><b>GRANDCHILD LABEL</b><br/>Label for grandchild items<br/>Identification text<br/>Grandchild identification"]
        end
    end
    
    %% HUGE Components and Text - Seventh Level
    subgraph "🧩 HUGE COMPONENTS AND TEXT SYSTEM"
        direction TB
        
        COMPONENT_BLOCK["🧩 Component<br/><b>BASIC BUILDING BLOCK</b><br/>Fundamental UI component<br/>Core visual element<br/>Primary UI building block"]
        
        TEXT_DETAIL_BLOCK["📝 TextDetail<br/><b>RICH TEXT CONTENT</b><br/>Formatted text with styling<br/>Text presentation system<br/>Advanced text management"]
        
        subgraph "🧩 HUGE COMPONENT PROPERTIES"
            COMPONENT_STYLE_ID["🎨 StyleID: string<br/><b>COMPONENT STYLE ID</b><br/>Style reference for component<br/>Styling identifier<br/>Component style reference"]
            
            COMPONENT_TEXT["📝 Text: string<br/><b>COMPONENT DISPLAY TEXT</b><br/>Text content for component<br/>User-visible text<br/>Component text content"]
            
            COMPONENT_TYPE["🏷️ Type: string<br/><b>COMPONENT TYPE</b><br/>Type of component<br/>Component classification<br/>Component categorization"]
            
            COMPONENT_VARS["🔗 Vars: *[]string<br/><b>DYNAMIC VARIABLES</b><br/>Variables for component<br/>Dynamic content control<br/>Component variable system"]
            
            COMPONENT_IMAGE_URL["🖼️ ImageURL: string<br/><b>COMPONENT IMAGE SOURCE</b><br/>Image source for component<br/>Visual content URL<br/>Component image system"]
        end
        
        subgraph "📝 HUGE TEXT DETAIL PROPERTIES"
            TEXT_DETAIL_COMPONENTS["🧩 Components: []Component<br/><b>TEXT DETAIL COMPONENTS</b><br/>Components within text detail<br/>Nested components<br/>Text detail component system"]
            
            TEXT_DETAIL_STYLE_ID["🎨 StyleID: string<br/><b>TEXT DETAIL STYLE ID</b><br/>Style reference for text detail<br/>Text styling identifier<br/>Text detail style reference"]
        end
    end
    
    %% MASSIVE Bottom Sheets System - Eighth Level
    subgraph "📱 MASSIVE BOTTOM SHEETS SYSTEM"
        direction TB
        
        BOTTOMSHEETS_CONTAINER["📱 BottomSheets<br/><b>MODAL DIALOG SYSTEM</b><br/>Complete modal dialog framework<br/>User interaction modals<br/>Dialog management system"]
        
        CONFIRMATION_DIALOG["✅ Confirmation<br/><b>CONFIRMATION DIALOG</b><br/>User confirmation modals<br/>Decision-making interface<br/>Confirmation management"]
        
        subgraph "🎨 HUGE MODAL COMPONENTS"
            BOTTOMSHEET_WIDGET["🎨 BottomSheetWidget<br/><b>MODAL WIDGET</b><br/>Widget within modal dialog<br/>Modal content element<br/>Modal widget system"]
            
            BOTTOMSHEET_CTA_DATA["🔘 BottomSheetCtaData<br/><b>MODAL CTA DATA</b><br/>Call-to-action data for modal<br/>Modal interaction element<br/>Modal CTA system"]
            
            BOTTOMSHEET_CTA["🔘 BottomSheetCTA<br/><b>MODAL CALL TO ACTION</b><br/>Interactive element in modal<br/>User action button<br/>Modal action system"]
        end
        
        subgraph "🖼️ HUGE MODAL ELEMENTS"
            LEFT_ICON["🖼️ LeftIcon<br/><b>WIDGET ICON</b><br/>Icon for modal widgets<br/>Visual indicator<br/>Modal icon system"]
            
            BOTTOMSHEET_TEXT["📝 BottomSheetText<br/><b>WIDGET TEXT</b><br/>Text content in modal<br/>Modal text content<br/>Modal text system"]
        end
        
        subgraph "📊 HUGE MODAL ANALYTICS"
            STATIC_ANALYTICS["📊 StaticAnalyticsData<br/><b>MODAL ANALYTICS</b><br/>Analytics for modal interactions<br/>User behavior tracking<br/>Modal analytics system"]
        end
    end
    
    %% HUGE CTA System - Ninth Level
    subgraph "🔘 HUGE CTA SYSTEM"
        direction TB
        
        CTA_BLOCK["🔘 CTA<br/><b>CALL TO ACTION</b><br/>Interactive button or link<br/>User interaction element<br/>Action management system"]
        
        subgraph "🔘 HUGE CTA PROPERTIES"
            CTA_LABEL["🏷️ Label: string<br/><b>CTA BUTTON TEXT</b><br/>Text displayed on button<br/>User-visible label<br/>CTA text system"]
            
            CTA_URL["🌐 URL: string<br/><b>CTA DESTINATION URL</b><br/>Link destination<br/>Navigation target<br/>CTA navigation system"]
            
            CTA_TYPE["🏷️ Type: string<br/><b>CTA ACTION TYPE</b><br/>Type of action performed<br/>Action classification<br/>CTA type system"]
            
            CTA_ID["🆔 ID: string<br/><b>CTA UNIQUE IDENTIFIER</b><br/>Unique ID for CTA<br/>Element identification<br/>CTA identification system"]
            
            CTA_ADDITIONAL_DATA["📋 AdditionalData: *CtaAdditionalData<br/><b>CTA ADDITIONAL DATA</b><br/>Extra data for CTA<br/>Additional configuration<br/>CTA data system"]
            
            CTA_ANALYTICS["📊 Analytics: *Analytics<br/><b>CTA ANALYTICS</b><br/>Analytics for CTA interactions<br/>User behavior tracking<br/>CTA analytics system"]
        end
        
        subgraph "📋 HUGE CTA ADDITIONAL DATA"
            CTA_ADDITIONAL_REPLACE["🔄 ReplaceTitleLayout: string<br/><b>TITLE REPLACEMENT LAYOUT</b><br/>Layout for title replacement<br/>Dynamic title control<br/>Title replacement system"]
            
            CTA_ADDITIONAL_ID["🆔 CtaId: string<br/><b>CTA ID</b><br/>CTA identifier<br/>Element reference<br/>CTA reference system"]
        end
    end
    
    %% MASSIVE Analytics System - Tenth Level
    subgraph "📊 MASSIVE ANALYTICS SYSTEM"
        direction TB
        
        ANALYTICS_BLOCK["📊 Analytics<br/><b>DYNAMIC ANALYTICS</b><br/>User behavior tracking<br/>System monitoring<br/>Analytics management system"]
        
        subgraph "📊 HUGE ANALYTICS PROPERTIES"
            ANALYTICS_PRODUCT["📱 Product: string<br/><b>PRODUCT NAME</b><br/>Product being tracked<br/>Application identifier<br/>Product tracking system"]
            
            ANALYTICS_SCREEN["📺 ScreenName: string<br/><b>SCREEN NAME</b><br/>Current screen being viewed<br/>Page identifier<br/>Screen tracking system"]
            
            ANALYTICS_TITLE["🏷️ Title: string<br/><b>EVENT TITLE</b><br/>Title of the event<br/>Event identification<br/>Event title system"]
            
            ANALYTICS_VENUE["🏢 VenueCode: string<br/><b>VENUE CODE</b><br/>Venue identifier<br/>Location tracking<br/>Venue tracking system"]
            
            ANALYTICS_METADATA["📊 Metadata: string<br/><b>ADDITIONAL METADATA</b><br/>Extra tracking information<br/>Context data<br/>Metadata tracking system"]
            
            ANALYTICS_CATEGORY["📂 Category: string<br/><b>EVENT CATEGORY</b><br/>Category of the event<br/>Event classification<br/>Category tracking system"]
            
            ANALYTICS_SUBCATEGORY["📂 SubCategory: string<br/><b>EVENT SUBCATEGORY</b><br/>Subcategory of the event<br/>Detailed classification<br/>Subcategory tracking system"]
            
            ANALYTICS_EVENT_NAME["🎭 EventName: string<br/><b>EVENT NAME</b><br/>Name of the event<br/>Event identification<br/>Event name system"]
            
            ANALYTICS_EVENT_TYPE["🏷️ EventType: string<br/><b>EVENT TYPE</b><br/>Type of the event<br/>Event classification<br/>Event type system"]
            
            ANALYTICS_EVENT_CODE["🆔 EventCode: string<br/><b>EVENT CODE</b><br/>Code for the event<br/>Event reference<br/>Event code system"]
            
            ANALYTICS_EVENT_GROUP["👥 EventGroup: string<br/><b>EVENT GROUP</b><br/>Group the event belongs to<br/>Event organization<br/>Event group system"]
            
            ANALYTICS_GENRE["🎨 Genre: string<br/><b>EVENT GENRE</b><br/>Genre of the event<br/>Event category<br/>Genre tracking system"]
            
            ANALYTICS_SUBGENRE["🎨 SubGenre: string<br/><b>EVENT SUBGENRE</b><br/>Subgenre of the event<br/>Detailed genre<br/>Subgenre tracking system"]
            
            ANALYTICS_LANGUAGE["🗣️ Language: string<br/><b>EVENT LANGUAGE</b><br/>Language of the event<br/>Localization<br/>Language tracking system"]
            
            ANALYTICS_PRICE["💰 Price: string<br/><b>EVENT PRICE</b><br/>Price of the event<br/>Cost information<br/>Price tracking system"]
            
            ANALYTICS_TRANSACTION_ID["🆔 TransactionID: string<br/><b>TRANSACTION ID</b><br/>Transaction identifier<br/>Payment tracking<br/>Transaction tracking system"]
            
            ANALYTICS_IS_TVOD["📺 IsTvod: string<br/><b>IS TVOD</b><br/>TVOD status<br/>Content type<br/>TVOD tracking system"]
        end
    end
    
    %% HUGE Footer Structure - Eleventh Level
    subgraph "🦶 HUGE FOOTER STRUCTURE"
        direction TB
        
        FOOTER_ITEM_DATA["🦶 TicketResaleFooterItemData<br/><b>FOOTER ITEM DATA</b><br/>Data for footer items<br/>Footer content container<br/>Footer data management"]
        
        subgraph "🦶 HUGE FOOTER PROPERTIES"
            FOOTER_TYPE["🏷️ Type: string<br/><b>FOOTER TYPE</b><br/>Type of footer item<br/>Footer classification<br/>Footer type system"]
            
            FOOTER_STYLE_ID["🎨 StyleID: string<br/><b>FOOTER STYLE ID</b><br/>Style reference for footer<br/>Footer styling<br/>Footer style system"]
            
            FOOTER_DATA["📋 Data: FooterParentData<br/><b>FOOTER PARENT DATA</b><br/>Parent data for footer<br/>Footer data container<br/>Footer parent system"]
        end
        
        FOOTER_PARENT_DATA["📋 FooterParentData<br/><b>FOOTER PARENT CONTAINER</b><br/>Parent container for footer<br/>Footer data organization<br/>Footer parent management"]
        
        FOOTER_CHILD_DATA["📄 FooterChildData<br/><b>FOOTER CHILD DATA</b><br/>Child data for footer<br/>Footer item details<br/>Footer child management"]
        
        subgraph "📄 HUGE FOOTER CHILD PROPERTIES"
            FOOTER_CHILD_LABEL["🏷️ Label: string<br/><b>FOOTER LABEL</b><br/>Label for footer item<br/>Footer identification<br/>Footer label system"]
            
            FOOTER_CHILD_TEXT["📝 Text: []TextDetail<br/><b>FOOTER TEXT</b><br/>Text content for footer<br/>Footer text content<br/>Footer text system"]
            
            FOOTER_CHILD_CTA["🔘 CTA: *CTA<br/><b>FOOTER CTA</b><br/>Call-to-action for footer<br/>Footer interaction<br/>Footer action system"]
        end
    end
    
    %% HUGE Start Actions - Twelfth Level
    subgraph "⚡ HUGE START ACTIONS"
        direction TB
        
        START_ACTIONS["⚡ StartActions<br/><b>INITIALIZATION ACTIONS</b><br/>Actions performed at startup<br/>System initialization<br/>Startup management system"]
        
        subgraph "⚡ HUGE START ACTION PROPERTIES"
            START_ACTION_ICON["🖼️ IconUrl: string<br/><b>ACTION ICON URL</b><br/>URL for action icon<br/>Visual indicator<br/>Action icon system"]
            
            START_ACTION_CTA["🔘 CTA: *CTA<br/><b>ACTION CTA</b><br/>Call-to-action for start action<br/>User interaction<br/>Start action system"]
        end
    end
    
    %% HUGE Style Details - Thirteenth Level
    subgraph "🎨 HUGE STYLE DETAILS"
        direction TB
        
        STYLE_DETAILS["🎨 StyleDetails<br/><b>STYLING INFORMATION</b><br/>Visual styling data<br/>Appearance control<br/>Style management system"]
        
        STYLE_AXIS["📐 Axis: string<br/><b>LAYOUT AXIS</b><br/>Layout direction control<br/>Orientation setting<br/>Layout axis system"]
    end
    
    %% MASSIVE Main Connections
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
    
    %% Apply ULTRA-LARGE Styling Classes
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

## MAGNIFIED Static Widget System Overview

### 🎯 **MASSIVE STATIC RESPONSE LAYER**
- **TicketResaleStaticInfoResponse**: Main API response container with **ULTRA-LARGE** text
- **StaticInfoData**: Core static data container with **MASSIVE** descriptions
- **Message**: Response status and feedback with **HUGE** text
- **Metadata**: Analytics and error handling with **LARGE** descriptions

### 📊 **HUGE STATIC DATA STRUCTURE**
- **Meta**: Version control and system metadata with **MASSIVE** text
- **Styles**: CSS-like styling system with **ULTRA-LARGE** descriptions
- **Layouts**: Layout container system with **HUGE** text
- **BottomSheets**: Modal dialog system with **LARGE** descriptions
- **StaticActions**: Predefined action system with **MASSIVE** text

### 📋 **LARGE META AND STYLING SYSTEM**
- **Version**: Layout version control with **ULTRA-LARGE** text
- **Style Definitions**: Key-value styling pairs with **HUGE** descriptions
- **Action Definitions**: Predefined system actions with **MASSIVE** text

### 📐 **MASSIVE LAYOUT SYSTEM**
- **Layout Container**: Main layout management with **ULTRA-LARGE** text
- **9 Layout Containers**: Footer, Header, Amount, Details, FAQ, Important, Replace, Separator with **HUGE** descriptions

### 📄 **HUGE LAYOUT ITEMS SYSTEM**
- **MasterLayoutItem**: Base layout component with **MASSIVE** text
- **ParentData**: Parent-level data container with **ULTRA-LARGE** descriptions
- **ChildData**: Child-level data container with **HUGE** text
- **GrandChildData**: Grandchild-level data container with **LARGE** descriptions

### 📊 **MASSIVE DATA STRUCTURE DETAILS**
- **Parent Data Properties**: Title, actions, style, data with **ULTRA-LARGE** text
- **Child Data Properties**: Style, data array, title, expansion, CTA, components, image with **HUGE** descriptions
- **GrandChild Data Properties**: Style ID, components, text detail, CTA, data array, style, label with **MASSIVE** text

### 🧩 **HUGE COMPONENTS AND TEXT SYSTEM**
- **Component**: Basic UI building block with **ULTRA-LARGE** text
- **TextDetail**: Rich text content with **HUGE** descriptions
- **Component Properties**: Style ID, text, type, variables, image URL with **MASSIVE** text
- **Text Detail Properties**: Components, style ID with **LARGE** descriptions

### 📱 **MASSIVE BOTTOM SHEETS SYSTEM**
- **BottomSheets**: Modal dialog framework with **ULTRA-LARGE** text
- **Confirmation**: User confirmation modals with **HUGE** descriptions
- **Modal Components**: Widgets, CTAs, icons, text with **MASSIVE** text
- **Modal Analytics**: User behavior tracking with **LARGE** descriptions

### 🔘 **HUGE CTA SYSTEM**
- **CTA**: Call-to-action buttons and links with **ULTRA-LARGE** text
- **CTA Properties**: Label, URL, type, ID, additional data, analytics with **HUGE** descriptions
- **CTA Additional Data**: Title replacement, CTA ID with **MASSIVE** text

### 📊 **MASSIVE ANALYTICS SYSTEM**
- **Analytics**: Comprehensive user behavior tracking with **ULTRA-LARGE** text
- **Analytics Properties**: Product, screen, title, venue, metadata, category, event details, price, transaction with **HUGE** descriptions

### 🦶 **HUGE FOOTER STRUCTURE**
- **Footer Item Data**: Footer content container with **MASSIVE** text
- **Footer Properties**: Type, style ID, data with **ULTRA-LARGE** descriptions
- **Footer Parent/Child Data**: Hierarchical footer organization with **HUGE** text

### ⚡ **HUGE START ACTIONS**
- **StartActions**: System initialization actions with **LARGE** text
- **Start Action Properties**: Icon URL, CTA with **MASSIVE** descriptions

### 🎨 **HUGE STYLE DETAILS**
- **StyleDetails**: Visual styling information with **ULTRA-LARGE** text
- **Style Properties**: Layout axis control with **HUGE** descriptions

## Key Features

### 🎯 **ULTRA-LARGE Design**
- **MASSIVE Blocks**: Each component has **HUGE** amounts of space
- **GIANT Text**: **24px** for main components, down to **12px** for properties
- **MAXIMUM Separation**: **MASSIVE** visual gaps between all sections
- **ULTRA-LARGE Margins**: **HUGE** spacing around all elements

### 🎨 **MAGNIFIED Styling**
- **ULTRA-LARGE Font Sizes**: **24px** for main, **22px** for subsystems, **20px** for layouts, **18px** for containers, **16px** for items, **14px** for components, **12px** for properties
- **MASSIVE Stroke Weights**: **8px** for main, **6px** for subsystems, **5px** for layouts, **4px** for containers, **3px** for items, **2px** for properties
- **HUGE Color Coding**: Different colors for different system layers
- **ULTRA-LARGE Contrast**: **MAXIMUM** readability

### 📊 **MASSIVE Coverage**
- **Complete System**: All static widget components with **HUGE** text
- **ULTRA-Detailed Information**: Full property and configuration details with **MASSIVE** descriptions
- **GIANT Hierarchy**: Visual hierarchy with **ULTRA-LARGE** spacing
- **MASSIVE Navigation**: Logical flow and organization with **HUGE** text

## Usage
- **PRESENTATIONS**: Perfect for **LARGE** screens and **MASSIVE** displays
- **DOCUMENTATION**: **ULTRA-READABLE** static widget architecture
- **TEAM COLLABORATION**: **HUGE** text for easy reading from distance
- **CONFERENCE ROOMS**: **MASSIVE** diagrams for **LARGE** audiences
