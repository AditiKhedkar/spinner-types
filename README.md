Deployed on  https://spinner-types.netlify.app/


<img width="1254" height="629" alt="image" src="https://github.com/user-attachments/assets/3ba6ceca-6ef5-478e-9c65-90a43b03da19" />


readme format 


**Features**:
- Grid-based layout for navigation cards
- Interactive preview animations
- Responsive design with auto-fit grid
- Hover effects with transform and shadow transitions

**Key CSS Classes**:
- `.nav-grid`: CSS Grid with auto-fit columns (min 300px)
- `.nav-card`: Card component with hover animations
- `.preview-*`: Visual previews for each navigation type

### 2. Horizontal Navigation Component
**File**: `src/app/components/horizontal-nav/horizontal-nav.component.ts`
**Purpose**: Traditional horizontal navigation bar
**Features**:
- Sticky positioning with box-shadow
- Active state management
- Hover transitions
- Responsive typography scaling

**Implementation Details**:
- Uses flexbox for layout alignment
- Sticky positioning (`position: sticky; top: 0`)
- Z-index layering for proper stacking
- Active state tracking with Angular property binding

### 3. Sidebar Navigation Component
**File**: `src/app/components/sidebar-nav/sidebar-nav.component.ts`
**Purpose**: Vertical sidebar navigation for dashboard layouts
**Features**:
- Fixed positioning sidebar
- Icon + text layout
- Scrollable content area
- Mobile responsive (hidden on small screens)

