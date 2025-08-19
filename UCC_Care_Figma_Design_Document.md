# UCC Care Mental Health Platform - Complete Figma Design Documentation

## 📋 Project Overview

**UCC Care** is a comprehensive mental health support platform designed specifically for university students. The platform provides confidential counseling services, wellness tracking, resource access, and secure communication between students, counselors, and administrators.

### Core Purpose

- Provide confidential mental health support for university students
- Enable secure communication between students and professional counselors
- Offer comprehensive resource library for self-help and wellness
- Maintain strict privacy and security standards (HIPAA/FERPA compliant)

---

## 🎨 Design System & Brand Identity

### Color Palette (Mental Health Focused)

The color scheme is specifically designed for mental wellness and trust-building:

**Primary Colors:**

- **Calm Blue**: `hsl(195, 85%, 45%)` - Primary brand color, trust and stability
- **Primary Foreground**: `hsl(0, 0%, 100%)` - White text on primary

**Secondary Colors:**

- **Comfort Lavender**: `hsl(250, 25%, 95%)` - Soft, comforting backgrounds
- **Secondary Foreground**: `hsl(215, 25%, 27%)` - Dark text

**Accent Colors:**

- **Hope Green**: `hsl(140, 30%, 90%)` - Success states and positive actions
- **Trust Teal**: `hsl(180, 50%, 75%)` - Secondary accents

**Status Colors:**

- **Success**: `hsl(140, 60%, 50%)` - Positive feedback and confirmations
- **Warning**: `hsl(45, 90%, 60%)` - Gentle alerts and important notices
- **Destructive**: `hsl(355, 70%, 60%)` - Soft coral for critical actions

**Neutral Colors:**

- **Background**: `hsl(210, 20%, 98%)` - Main page background
- **Foreground**: `hsl(215, 25%, 27%)` - Primary text
- **Muted**: `hsl(210, 20%, 96%)` - Subtle backgrounds
- **Border**: `hsl(215, 20%, 88%)` - Element separators

### Dark Mode Support

All colors have corresponding dark mode variants with adjusted HSL values for accessibility and eye comfort during extended use.

### Typography & Spacing

- **Border Radius**: `0.75rem` (12px) - Soft, friendly edges throughout
- **Container Max Width**: `1400px` with centered alignment
- **Responsive Breakpoints**: Mobile-first design with 2xl breakpoint at 1400px

---

## 👥 User Roles & Interface Architecture

### 1. **Student Interface**

_Target Users: University students seeking mental health support_

**Entry Points:**

- Landing page with clear role selection
- Student login (`/student/login`)
- Multi-step registration (`/student/register`)

**Core Dashboard Features:**

- Personal wellness tracking with mood logs
- Quick access to confidential report submission
- Resource library with categorized content
- Secure communication with assigned counselors
- Privacy settings and consent management

### 2. **Counselor Interface**

_Target Users: Licensed mental health professionals_

**Entry Points:**

- Professional login with institutional verification
- Secure dashboard access (`/counselor/dashboard`)

**Core Management Features:**

- Case prioritization system (urgent/high/medium/low)
- Secure student communication interface
- Private case notes and documentation
- Resource recommendation tools
- Workload and schedule management

### 3. **Administrator Interface**

_Target Users: Platform administrators and institutional staff_

**Entry Points:**

- High-security login with 2FA requirement
- System-wide management console (`/admin/dashboard`)

**Core Administrative Features:**

- User account management across all roles
- Platform analytics and usage statistics
- Resource content management system
- Security audit logs and compliance monitoring
- System configuration and policy management

---

## 🗺️ Complete Page Structure & Layouts

### **Public Pages**

#### 1. Landing Page (`/`)

**Layout Structure:**

- **Hero Section**: Clear value proposition with calming imagery
- **Role Selection Cards**: Student, Counselor, Admin access points
- **Trust Indicators**: Privacy badges, security certifications
- **Quick Access**: Anonymous reporting option prominently displayed
- **Footer**: Contact information, crisis resources, privacy policy

#### 2. Anonymous Report (`/anonymous-report`)

**Layout Structure:**

- **Progress Indicator**: Multi-step form completion status
- **Privacy Assurance**: Clear explanation of anonymity protection
- **Form Sections**:
  - Issue description with guided prompts
  - Urgency level selection with clear indicators
  - Optional demographic information
- **Tracking ID Generation**: Prominent display of unique identifier
- **Next Steps**: Clear instructions for follow-up access

#### 3. Resource Library (`/resources`)

**Layout Structure:**

- **Search & Filter Bar**: Category tags, content type filters
- **Resource Grid**: Card-based layout with thumbnails
- **Quick Access Sections**: Crisis resources, popular content
- **Resource Detail View**: Content with engagement tracking
- **Related Content**: Personalized recommendations

### **Student Pages**

#### 4. Student Login (`/student/login`)

**Layout Structure:**

- **Clean Form Design**: Email, password, remember me option
- **Security Features**: Password visibility toggle, strength indicator
- **Alternative Actions**: Registration link, password reset
- **Privacy Reminder**: Confidentiality assurance messaging

#### 5. Student Registration (`/student/register`)

**Multi-Step Layout:**

- **Step 1 - Personal Information**: Basic details with privacy explanation
- **Step 2 - Emergency Contacts**: Required safety information
- **Step 3 - Security Setup**: Password creation with strength requirements
- **Step 4 - Consent & Terms**: Clear privacy policy agreement
- **Progress Tracking**: Visual step completion indicator

#### 6. Student Dashboard (`/student/dashboard`)

**Layout Sections:**

- **Welcome Header**: Personalized greeting with quick stats
- **Mood Tracking Widget**: Visual mood entry with trend display
- **Quick Actions Panel**: Report submission, resource access, messages
- **Recent Activity**: Case updates, resource history
- **Wellness Insights**: Personal progress tracking
- **Emergency Resources**: Always-visible crisis support

#### 7. Authenticated Report (`/report`)

**Layout Structure:**

- **Pre-filled Information**: Student details auto-populated
- **Enhanced Form Fields**: Detailed issue categorization
- **Attachment Options**: File upload for relevant documents
- **Communication Preferences**: How student wants to be contacted
- **Case Assignment**: Automatic or preferred counselor selection

#### 8. Report Status Tracking (`/report-status`)

**Layout Structure:**

- **Case Overview**: Status timeline with clear progress indicators
- **Communication Thread**: Secure messaging interface
- **Document Sharing**: Safe file exchange area
- **Satisfaction Feedback**: Case resolution rating system

### **Counselor Pages**

#### 9. Counselor Login (`/counselor/login`)

**Professional Layout:**

- **Institutional Branding**: University/organization logos
- **Enhanced Security**: Multi-factor authentication prompts
- **Professional Verification**: Credential confirmation process
- **Quick Access**: Emergency case notifications

#### 10. Counselor Dashboard (`/counselor/dashboard`)

**Professional Interface:**

- **Case Priority Queue**: Color-coded urgency system
- **Active Cases Panel**: Current assignments with quick actions
- **Calendar Integration**: Appointment scheduling and reminders
- **Resource Tools**: Quick access to professional materials
- **Workload Analytics**: Personal performance and case metrics
- **Communication Center**: Secure messaging with students

### **Administrator Pages**

#### 11. Admin Login (`/admin/login`)

**High-Security Layout:**

- **Two-Factor Authentication**: Mandatory security verification
- **Access Logging**: Real-time login attempt monitoring
- **Role Verification**: Administrative privilege confirmation
- **System Health**: Quick platform status overview

#### 12. Admin Dashboard (`/admin/dashboard`)

**Comprehensive Management Interface:**

- **System Overview**: Platform-wide statistics and health metrics
- **User Management**: Account creation, modification, deactivation
- **Content Management**: Resource library administration
- **Analytics Dashboard**: Usage patterns, engagement metrics
- **Security Monitoring**: Audit logs, compliance reporting
- **Configuration Panel**: System settings and policy management

---

## 🔧 Component Library & UI Patterns

### **Navigation Components**

- **Main Navigation**: Role-aware menu system
- **Breadcrumbs**: Clear page hierarchy
- **Sidebar Navigation**: Collapsible menu for dashboards
- **Footer Navigation**: Legal, support, and resource links

### **Form Components**

- **Input Fields**: Consistent styling with validation states
- **Select Dropdowns**: Searchable options with clear labeling
- **Radio/Checkbox Groups**: Clear selection indicators
- **File Upload**: Drag-and-drop with progress indicators
- **Form Validation**: Real-time feedback with helpful error messages

### **Data Display Components**

- **Cards**: Content containers with consistent padding and shadows
- **Tables**: Sortable, filterable data displays
- **Progress Indicators**: Step completion and loading states
- **Charts & Graphs**: Wellness tracking and analytics visualization
- **Status Badges**: Color-coded indicators for case priorities

### **Interactive Components**

- **Buttons**: Primary, secondary, and destructive action styles
- **Modals & Dialogs**: Confirmation and detail view overlays
- **Tooltips**: Contextual help and information
- **Accordion/Collapsible**: Organized information disclosure
- **Tabs**: Content organization and navigation

### **Feedback Components**

- **Toast Notifications**: Success, warning, and error messages
- **Loading States**: Skeleton screens and spinners
- **Empty States**: Helpful messaging when no content exists
- **Error Boundaries**: Graceful failure handling

---

## 🔐 Security & Privacy Design Considerations

### **Visual Trust Indicators**

- **Privacy Badges**: Visible security certifications
- **Encryption Indicators**: Visual confirmation of data protection
- **Anonymous Options**: Clear identification of anonymous features
- **Confidentiality Reminders**: Consistent messaging about privacy

### **Access Control Visual Cues**

- **Role-Based UI**: Different interfaces for different user types
- **Permission Indicators**: Clear visual feedback for access levels
- **Session Management**: Visible login status and timeout warnings
- **Audit Trail Visualization**: Transparent activity logging

---

## 📱 Responsive Design Requirements

### **Mobile-First Approach**

- **Touch-Friendly**: Minimum 44px touch targets
- **Readable Text**: Optimized font sizes for mobile screens
- **Simplified Navigation**: Collapsible menus and clear hierarchy
- **Quick Actions**: One-tap access to critical features

### **Tablet Optimization**

- **Adaptive Layouts**: Utilize available screen real estate
- **Enhanced Input**: Support for both touch and keyboard input
- **Multi-Column Layouts**: Efficient information display

### **Desktop Experience**

- **Multi-Panel Layouts**: Efficient use of large screens
- **Keyboard Navigation**: Full accessibility support
- **Advanced Features**: Complex data visualization and management tools

---

## 🔄 User Flows & Journey Mapping

### **Critical User Journeys**

#### **Emergency Support Flow**

1. **Discovery**: Anonymous reporting prominently displayed
2. **Immediate Access**: No registration required for crisis support
3. **Triage**: Automatic priority assignment based on urgency
4. **Rapid Response**: Expedited counselor notification and response
5. **Follow-up**: Continued support and resource provision

#### **Routine Support Flow**

1. **Registration**: Guided account creation with privacy assurance
2. **Dashboard Familiarization**: Onboarding tour of available features
3. **Report Submission**: Detailed issue description with category selection
4. **Counselor Assignment**: Automatic matching or student preference
5. **Ongoing Communication**: Secure messaging until resolution
6. **Feedback & Closure**: Case satisfaction and follow-up resources

#### **Counselor Case Management Flow**

1. **Daily Login**: Security verification and case queue review
2. **Priority Assessment**: Urgent cases highlighted for immediate attention
3. **Case Review**: Student information and issue analysis
4. **Response Planning**: Resource gathering and communication strategy
5. **Student Engagement**: Secure messaging and support provision
6. **Case Documentation**: Progress notes and outcome tracking
7. **Case Closure**: Resolution confirmation and follow-up planning

### **Accessibility Requirements**

- **WCAG 2.1 AA Compliance**: Full accessibility standard adherence
- **Screen Reader Support**: Semantic HTML and ARIA labels
- **Keyboard Navigation**: Complete functionality without mouse
- **Color Contrast**: Minimum 4.5:1 ratio for all text
- **Alternative Text**: Descriptive alt text for all images
- **Focus Management**: Clear visual focus indicators

---

## 📊 Data Visualization & Analytics

### **Student Wellness Tracking**

- **Mood Charts**: Trend visualization with color-coded indicators
- **Progress Graphs**: Goal achievement and milestone tracking
- **Engagement Metrics**: Resource usage and interaction patterns

### **Counselor Performance Dashboards**

- **Caseload Visualization**: Active cases with priority distribution
- **Response Time Metrics**: Communication efficiency tracking
- **Outcome Analytics**: Case resolution success rates

### **Administrative Analytics**

- **Platform Usage**: User engagement and feature adoption
- **System Performance**: Technical metrics and health monitoring
- **Compliance Reporting**: Privacy and security audit visualization

---

## 🚀 Technical Implementation Notes for Design

### **Component Architecture**

- **Atomic Design**: Button → Card → Dashboard pattern
- **Consistent Spacing**: 8px grid system throughout
- **Standardized Animations**: Smooth transitions for state changes
- **Icon Library**: Lucide React for consistent iconography

### **State Management Patterns**

- **Loading States**: Skeleton screens for better perceived performance
- **Error Handling**: Graceful degradation with clear error messaging
- **Form Validation**: Real-time feedback with clear success indicators

### **Performance Considerations**

- **Progressive Loading**: Critical content first, progressive enhancement
- **Image Optimization**: Proper sizing and format selection
- **Code Splitting**: Route-based loading for faster initial page loads

---

## 🎯 Design Priorities & Principles

### **Core Design Principles**

1. **Trust & Safety**: Every design decision reinforces user confidence
2. **Accessibility First**: Universal design for all users
3. **Privacy by Design**: Visual confirmation of data protection
4. **Calming Aesthetics**: Reduce anxiety through thoughtful design
5. **Clear Communication**: Remove ambiguity in all interactions

### **Success Metrics**

- **User Engagement**: Time spent on platform, feature adoption
- **Case Resolution**: Successful completion rates and satisfaction
- **Accessibility**: Compliance metrics and user feedback
- **Performance**: Page load times and interaction responsiveness
- **Trust Indicators**: User retention and privacy satisfaction

---

## 📝 Implementation Checklist for Figma

### **Design System Setup**

- [ ] Create color palette with HSL values provided
- [ ] Establish typography scale and spacing system
- [ ] Build component library with consistent styling
- [ ] Design responsive breakpoint system

### **Page Templates**

- [ ] Create all 12 page layouts with proper information architecture
- [ ] Design mobile, tablet, and desktop versions
- [ ] Include all user states (empty, loading, error, success)
- [ ] Add accessibility annotations and specifications

### **Component Library**

- [ ] Design all UI components with variants and states
- [ ] Create interaction specifications and micro-animations
- [ ] Document usage guidelines and accessibility requirements
- [ ] Build responsive behavior specifications

### **User Flow Documentation**

- [ ] Map complete user journeys for all three roles
- [ ] Design onboarding and tutorial flows
- [ ] Create error and edge case handling
- [ ] Document privacy and security visual indicators

This comprehensive documentation provides everything needed to recreate the UCC Care mental health platform in Figma, maintaining the careful balance of accessibility, security, and user-centered design that makes this platform effective for its sensitive and critical purpose.
