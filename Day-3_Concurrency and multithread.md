# NGÀY 3: CONCURRENCY & MULTITHREADING

## 1. Grand Central Dispatch (GCD)

### 1.1 Queue Architecture
#### 1.1.1 Queue Types
- [ ] Serial Queues
  - [ ] FIFO guarantee
  - [ ] Thread affinity
  - [ ] Synchronization patterns
- [ ] Concurrent Queues
  - [ ] Width management
  - [ ] Priority inheritance
  - [ ] Work stealing

#### 1.1.2 Queue Implementation
- [ ] Internal Structure
  - [ ] Thread pool management
  - [ ] Work item queuing
  - [ ] Priority handling
- [ ] Performance Characteristics
  - [ ] Queue overhead
  - [ ] Context switching
  - [ ] Memory impact

### 1.2 Dispatch Objects
#### 1.2.1 Dispatch Work Items
- [ ] Block Execution
  - [ ] Block copying
  - [ ] Stack frame setup
  - [ ] Exception handling
- [ ] Work Item Lifecycle
  - [ ] Creation overhead
  - [ ] Cancellation support
  - [ ] Completion handling

#### 1.2.2 Synchronization Tools
- [ ] Semaphores
  - [ ] Counter implementation
  - [ ] FIFO ordering
  - [ ] Timeout handling
- [ ] Dispatch Groups
  - [ ] Group synchronization
  - [ ] Notification handling
  - [ ] Hierarchical waiting

## 2. Operation Queues

### 2.1 NSOperation Design
#### 2.1.1 Operation States
- [ ] State Machine
  - [ ] State transitions
  - [ ] KVO notifications
  - [ ] Thread safety
- [ ] Dependencies
  - [ ] Dependency graph
  - [ ] Cycle detection
  - [ ] Priority inheritance

#### 2.1.2 Custom Operations
- [ ] Subclassing
  - [ ] Async operations
  - [ ] Progress reporting
  - [ ] Cancellation support
- [ ] Best Practices
  - [ ] State management
  - [ ] Memory management
  - [ ] Error handling

### 2.2 Queue Management
#### 2.2.1 Operation Scheduling
- [ ] Priority System
  - [ ] QoS integration
  - [ ] Priority calculation
  - [ ] Starvation prevention
- [ ] Execution Control
  - [ ] Maximum concurrent operations
  - [ ] Suspension handling
  - [ ] Operation reordering

#### 2.2.2 Advanced Features
- [ ] Operation Dependencies
  - [ ] Complex workflows
  - [ ] Cross-queue dependencies
  - [ ] Dependency conditions
- [ ] Operation Observers
  - [ ] Progress monitoring
  - [ ] Completion handling
  - [ ] Error propagation
