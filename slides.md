---
marp: true
theme: custom-product
paginate: true
math: katex
style: |
  /* Custom Theme: custom-product */
  @import 'default';
  
  :root {
    --primary-color: #2563eb;
    --secondary-color: #64748b;
    --accent-color: #f59e0b;
    --background-color: #f8fafc;
  }
  
  section {
    background: var(--background-color);
    font-family: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif;
    color: #1e293b;
    padding: 60px;
  }
  
  section h1 {
    color: var(--primary-color);
    font-weight: 700;
    border-bottom: 4px solid var(--accent-color);
    padding-bottom: 0.5em;
    margin-bottom: 1em;
  }
  
  section h2 {
    color: var(--primary-color);
    font-weight: 600;
    border-left: 5px solid var(--accent-color);
    padding-left: 1em;
  }
  
  section h3 {
    color: var(--secondary-color);
    font-weight: 500;
  }
  
  /* Page Numbers */
  section::after {
    content: "Page " attr(data-marpit-pagination) " of " attr(data-marpit-pagination-total);
    position: absolute;
    right: 40px;
    bottom: 20px;
    font-size: 0.9em;
    color: var(--secondary-color);
    background: white;
    padding: 8px 16px;
    border-radius: 20px;
    box-shadow: 0 2px 4px rgba(0,0,0,0.1);
  }
  
  /* Email styling */
  .email {
    background: var(--primary-color);
    color: white;
    padding: 4px 8px;
    border-radius: 4px;
    font-family: monospace;
  }
  
  /* Code blocks */
  section pre {
    background: #1e293b;
    color: #e2e8f0;
    border-radius: 8px;
    padding: 1.5em;
    box-shadow: 0 4px 6px rgba(0,0,0,0.1);
  }
  
  /* Math equations */
  section .katex-display {
    background: white;
    padding: 1em;
    border-radius: 8px;
    box-shadow: 0 2px 4px rgba(0,0,0,0.1);
    margin: 1em 0;
  }
  
  /* Title slide */
  section.title {
    background: linear-gradient(135deg, var(--primary-color) 0%, #1e40af 100%);
    color: white;
    text-align: center;
    justify-content: center;
  }
  
  section.title h1 {
    color: white;
    font-size: 3em;
    border-bottom: none;
    text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
  }
---

<!-- _class: title -->
<!-- _paginate: false -->

# Product Documentation
## API Integration Guide

**Technical Writer**  
<span class="email">22f3003115@ds.study.iitm.ac.in</span>

**August 2025**

---

## Table of Contents

**Presented by:** <span class="email">22f3003115@ds.study.iitm.ac.in</span>

1. **System Architecture** - Core Components Overview
2. **API Authentication** - Security Implementation
3. **Performance Analysis** - Algorithmic Complexity
4. **Integration Examples** - Code Samples
5. **Best Practices** - Development Guidelines
6. **Contact Information** - Support and Feedback

---

<!-- _backgroundImage: url('https://images.unsplash.com/photo-1451187580459-43490279c0fa?w=1200&h=800&fit=crop') -->
<!-- _class: invert -->

# System Architecture Overview

**Documentation by:** <span class="email">22f3003115@ds.study.iitm.ac.in</span>

## Microservices Platform

- **API Gateway**: Centralized request routing
- **Authentication Service**: OAuth 2.0 implementation  
- **Data Processing Engine**: Real-time analytics
- **Storage Layer**: Distributed database system
- **Monitoring Stack**: Observability and logging

---

## API Authentication Flow

**Author:** <span class="email">22f3003115@ds.study.iitm.ac.in</span>

