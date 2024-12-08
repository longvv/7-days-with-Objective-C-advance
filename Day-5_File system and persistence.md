# NGÀY 5: FILE SYSTEM & PERSISTENCE

## 1. File Operations

### 1.1 File System Access
#### 1.1.1 File Manager Operations
- [ ] Path Management
  - [ ] URL vs Path
  - [ ] Sandbox constraints
  - [ ] Directory structure
- [ ] File Operations
  - [ ] Atomic writes
  - [ ] Copy operations
  - [ ] Move operations

#### 1.1.2 File Handling
- [ ] Stream Operations
  - [ ] Buffer management
  - [ ] Chunk processing
  - [ ] Error handling
- [ ] File Coordination
  - [ ] Lock management
  - [ ] Version tracking
  - [ ] Conflict resolution

### 1.2 Data Reading/Writing
#### 1.2.1 Memory Mapping
- [ ] Map Implementation
  - [ ] Page alignment
  - [ ] Virtual memory
  - [ ] Cache management
- [ ] Performance
  - [ ] Read/write patterns
  - [ ] Page faults
  - [ ] Memory pressure

#### 1.2.2 File Attributes
- [ ] Metadata Management
  - [ ] Extended attributes
  - [ ] Resource forks
  - [ ] UTIs
- [ ] Security
  - [ ] File protection
  - [ ] Access control
  - [ ] Encryption

## 2. Persistence Strategies

### 2.1 NSCoding Implementation
#### 2.1.1 Archive Structure
- [ ] Data Format
  - [ ] Key encoding
  - [ ] Object graphs
  - [ ] Version support
- [ ] Security
  - [ ] Secure coding
  - [ ] Data validation
  - [ ] Error handling

#### 2.1.2 Performance
- [ ] Optimization
  - [ ] Lazy loading
  - [ ] Incremental archiving
  - [ ] Compression
- [ ] Memory Management
  - [ ] Buffer sizing
  - [ ] Temporary storage
  - [ ] Cleanup

### 2.2 Core Data
#### 2.2.1 Stack Configuration
- [ ] Store Types
  - [ ] SQLite
  - [ ] Binary
  - [ ] Memory
- [ ] Context Management
  - [ ] Concurrency
  - [ ] Parent/child
  - [ ] Merge policies

#### 2.2.2 Performance Tuning
- [ ] Fetch Optimization
  - [ ] Batch size
  - [ ] Prefetching
  - [ ] Cache configuration
- [ ] Save Operations
  - [ ] Batch processing
  - [ ] Background saving
  - [ ] Conflict resolution
