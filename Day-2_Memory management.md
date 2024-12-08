# NGÀY 2: MEMORY MANAGEMENT

## 1. Manual Memory Management (MRR)

### 1.1 Ownership Policy
#### 1.1.1 Basic Memory Rules
- [ ] Object Creation
  - [ ] alloc/new/copy/mutableCopy
  - [ ] Factory methods
  - [ ] Reference counting basics
- [ ] Ownership transfer
  - [ ] retain/release semantics 
  - [ ] Object lifecycle management
  - [ ] Ownership graphs

#### 1.1.2 Autorelease Pool
- [ ] Pool Implementation
  - [ ] Page-level memory management
  - [ ] Pool page data structure
  - [ ] Pop operation efficiency
- [ ] Pool Contexts
  - [ ] Runloop integration
  - [ ] Nested pools
  - [ ] Drain timing

### 1.2 Memory Debugging
#### 1.2.1 Leak Detection
- [ ] Static Analysis
  - [ ] Compiler warnings
  - [ ] Static analyzer
  - [ ] Code paths analysis
- [ ] Runtime Detection
  - [ ] Instruments usage
  - [ ] Memory graph
  - [ ] Leak patterns

#### 1.2.2 Tools & Techniques
- [ ] Debug Tools
  - [ ] Memory debugger
  - [ ] Malloc stack logging
  - [ ] Heap visualization
- [ ] Common Issues
  - [ ] Double release
  - [ ] Use after free
  - [ ] Stack vs heap allocations

## 2. Automatic Reference Counting (ARC)

### 2.1 ARC Implementation
#### 2.1.1 Compiler Optimizations
- [ ] Reference Counting
  - [ ] Side table implementation
  - [ ] Fast/slow paths
  - [ ] Runtime optimizations
- [ ] Retain/Release Elision
  - [ ] Local-scope optimization
  - [ ] Return value optimization
  - [ ] Temporary objects

#### 2.1.2 Runtime Support
- [ ] ARC Runtime
  - [ ] Object layout
  - [ ] Reference counting bits
  - [ ] Weak references table
- [ ] Performance Impact
  - [ ] Memory overhead
  - [ ] CPU overhead
  - [ ] Cache effects

### 2.2 Memory Management Patterns
#### 2.2.1 Object Relationships
- [ ] Parent-Child
  - [ ] Ownership cycles
  - [ ] Back-references
  - [ ] Collection relationships
- [ ] Delegates
  - [ ] Weak delegate pattern
  - [ ] Multi-delegate systems
  - [ ] Retain cycles prevention

#### 2.2.2 Block Memory Management
- [ ] Block Structure
  - [ ] Stack blocks
  - [ ] Heap blocks
  - [ ] Global blocks
- [ ] Variable Capture
  - [ ] Strong capture
  - [ ] Weak capture
  - [ ] Block copying

### 2.3 Advanced Memory Topics
#### 2.3.1 Tagged Pointers
- [ ] Implementation
  - [ ] Bit patterns
  - [ ] Available types
  - [ ] Platform differences
- [ ] Optimization
  - [ ] Memory savings
  - [ ] Performance gains
  - [ ] Usage detection

#### 2.3.2 Weak References
- [ ] Implementation Details
  - [ ] Weak table
  - [ ] Zero-ing mechanism
  - [ ] Race conditions
- [ ] Usage Patterns
  - [ ] Cache implementations
  - [ ] Observer patterns
  - [ ] Temporary references
