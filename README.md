# SmartWin App

> A Real-World Service Quality & Safety Feedback System for Motorcycle Taxi Services in Bangkok

## Project Overview

SmartWinThai is a feedback and reporting system designed to improve accountability and service quality in motorcycle taxi (Win motorbike) operations. Riders display QR codes that passengers can scan right after their trip, allowing people to instantly provide feedback about their experience with that specific rider. The platform enables users to rate specific riders and report concerns about specific service locations, creating a transparent mechanism for quality assurance and community safety in urban transportation services.


## Real-World Deployment

**Live in: พื้นที่เขตคลองสามวา (Khlong Samwa District), Bangkok**

SmartWin is currently operational in Khlong Samwa District, Bangkok, through a partnership with the Bangkok Metropolitan Administration. The system has been deployed to help streamline service quality monitoring and community feedback mechanisms for motorcycle taxi operations in this area.

- **Live Dashboard**: https://smartwinthai.xyz/?id=
- **Live Application**: https://app.smartwinthai.xyz/?area=
- **Community Page**: https://www.facebook.com/khlong3wa/ (SmartWin Smart Motorbike Initiative)

## Architecture: Dual Web Applications

SmartWin is strategically divided into **two complementary web applications** to serve different feedback mechanisms and use cases:

### Application 1: Rider-Specific Feedback System
**Purpose**: Direct accountability through individual rider performance tracking

Users can:
- Scan a rider's QR code immediately after their trip
- Rate individual rider performance (safety, professionalism, reliability)
- Submit detailed feedback or compliments about their experience with a specific rider
- Report safety concerns, misconduct, or service issues linked to a specific rider
- View aggregate ratings and feedback for individual riders

**Access**: `https://smartwinthai.xyz/?id=[RIDER_ID]`

### Application 2: Location-Based Service Quality System
**Purpose**: Area and zone-level service quality monitoring

Users can:
- Scan a rider's QR code immediately after their trip
- Report service quality issues specific to geographic locations (pickup points, common waiting areas)
- Provide feedback about service conditions in particular areas (e.g., availability, wait times, safety)
- Alert authorities to location-specific problems (congestion, unsafe practices, service gaps)
- View area-level service metrics and community feedback

**Access**: `https://app.smartwinthai.xyz/?area=[LOCATION_NAME]`

### Why Two Apps?

The dual-application approach addresses a critical principle: **accountability at two levels**. Individual rider performance drives personal responsibility, while location-based feedback helps authorities identify systemic issues that require operational or infrastructure changes.

## Key Features

**🎯 Individual Rider Accountability**
- Identify specific riders and provide direct feedback
- Transparent rating system for individual performance
- Historical record of service quality per rider
- Recognize excellent service and drivers

**📍 Location-Based Service Reporting**
- Report issues tied to specific geographic areas
- Identify service quality patterns across the district
- Alert authorities to systemic location-based problems
- Help optimize rider distribution and resource allocation

**📊 Data for Improvement**
- Aggregate feedback for administrative review
- Trend identification across areas and time periods
- Data-driven decision making for service improvements

**📱 Accessible Design**
- Mobile-friendly responsive interface
- Simple, intuitive rating system
- Thai language support for local users
- Quick feedback submission (minimal required fields)

## Risk Assessment & Security Considerations

**⚠️ Important Notice**

SmartWin is a functional, real-world system currently in deployment. However, the project acknowledges that it **contains significant security vulnerabilities and operational risks** that require ongoing remediation. A formal risk assessment has been conducted to identify and document these issues.

**Access:** [Risk assessment](https://docs.google.com/spreadsheets/d/1V8YJ9P_FUIEDGZkEj3y13c6h_5ot46C-kiD1utsRLuM/edit?gid=1391385484#gid=1391385484)

### Key Risk Areas Identified:

**Security Vulnerabilities**
- Data privacy concerns related to rider identification and feedback
- Potential for misuse of reporting system (false accusations, harassment)
- Authentication and authorization gaps
- Data storage and protection limitations
- API security weaknesses

**Operational Risks**
- Rider identification accuracy and verification
- Feedback manipulation or coordinated false reports
- Data integrity and audit trail concerns
- Complaint handling and due process procedures

**Community & Ethical Risks**
- Risk of feedback system being weaponized against specific riders
- Lack of appeals process for disputed feedback
- Transparency issues in how feedback is used
- Potential for discrimination based on feedback patterns

### Risk Mitigation Strategy

This project is intentionally maintaining transparency about its limitations. The risk assessment serves multiple purposes:

1. **Accountability**: Documenting known issues prevents claims of ignorance
2. **Improvement Roadmap**: Vulnerabilities guide development priorities
3. **Responsible Deployment**: Stakeholders understand constraints and risks
4. **Iterative Security**: Planned improvements address identified gaps

## Tech Stack

| Component | Technology |
|-----------|-----------|
| **Frontend Framework** | React.js |
| **Styling** | CSS3, Responsive Design |
| **State Management** | Context API / Redux |
| **API Communication** | Axios |
| **Maps/Locations** | Location APIs |
| **Language Support** | Thai, English |

## Contact

**Project Lead**: Kanika Imerb  
**GitHub**: [@kanikaimerb](https://github.com/kanikaimerb)  
**Community**: [Khlong Samwa District Facebook](https://www.facebook.com/khlong3wa/)
