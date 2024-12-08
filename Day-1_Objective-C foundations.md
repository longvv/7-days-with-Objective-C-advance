# NGÀY 1: NỀN TẢNG OBJECTIVE-C

## 1. Runtime System & Dynamic Dispatch

### 1.1 Runtime Architecture
#### 1.1.1 Object Model và ISA pointer
- [ ] Class structure trong memory
  - [ ] Class definition trong runtime
  - [ ] Instance variable layout
  - [ ] Method list structure
  - [ ] Protocol list structure
  - [ ] Property list structure
- [ ] ISA pointer implementation
  - [ ] Tagged pointers optimization
  - [ ] Non-pointer ISA optimizations
  - [ ] ISA swizzling techniques
- [ ] Class/metaclass relationship
  - [ ] Class object structure
  - [ ] Metaclass object structure
  - [ ] Root class special cases

#### 1.1.2 Method caching mechanism
- [ ] Cache structure
  - [ ] Implementation của method cache
  - [ ] Cache size và growth
  - [ ] Cache entry structure
- [ ] Cache lookup process
  - [ ] Hash function implementation
  - [ ] Collision handling
  - [ ] Cache invalidation triggers
- [ ] Cache optimization
  - [ ] Bucket distribution
  - [ ] Linear probing strategy
  - [ ] Cache coherency

### 1.2 Message Passing
#### 1.2.1 objc_msgSend flow
- [ ] Message structure
  - [ ] Selector lookup
  - [ ] Argument passing
  - [ ] Return value handling
- [ ] Fast path execution
  - [ ] Cached method lookup
  - [ ] Direct dispatch conditions
  - [ ] IMP caching
- [ ] Slow path handling
  - [ ] Method lookup steps
  - [ ] Forward invocation
  - [ ] Dynamic method resolution

#### 1.2.2 Method lookup process
- [ ] Class hierarchy traversal
  - [ ] Instance method lookup
  - [ ] Class method lookup
  - [ ] Category method precedence
- [ ] Method list searching
  - [ ] Linear vs binary search
  - [ ] Method name comparison
  - [ ] Method attributes checking
- [ ] Runtime optimization
  - [ ] Method inlining
  - [ ] Static vs dynamic dispatch
  - [ ] Virtual method table

### 1.3 Dynamic Method Resolution
#### 1.3.1 Method Swizzling Implementation
- [ ] Safe swizzling patterns
  - [ ] Load time swizzling
  - [ ] Method replacement safety
  - [ ] Selector validation
- [ ] Common use cases
  - [ ] Analytics injection
  - [ ] Method logging
  - [ ] Feature toggling
- [ ] Error handling
  - [ ] Missing method handling
  - [ ] Type checking
  - [ ] Exception safety

#### 1.3.2 Message Forwarding
- [ ] Forwarding stages
  - [ ] Dynamic method resolution
  - [ ] Fast forwarding
  - [ ] Normal forwarding
- [ ] Proxy implementation
  - [ ] Proxy object design
  - [ ] Method signature matching
  - [ ] Return value handling
- [ ] Performance implications
  - [ ] Forwarding overhead
  - [ ] Caching strategies
  - [ ] Memory management

## 2. Class Structure & Inheritance

### 2.1 Class Implementation
#### 2.1.1 Instance Variables
- [ ] Memory layout
  - [ ] Alignment requirements
  - [ ] Padding optimization
  - [ ] Size calculation
- [ ] Access patterns
  - [ ] Direct vs indirect access
  - [ ] Atomic operations
  - [ ] Thread safety
- [ ] Dynamic modification
  - [ ] Runtime ivar injection
  - [ ] KVO implications
  - [ ] Binary compatibility

#### 2.1.2 Property Implementation
- [ ] Attribute combinations
  - [ ] Atomic vs nonatomic
  - [ ] Strong vs weak vs copy
  - [ ] Readonly vs readwrite
- [ ] Synthesized methods
  - [ ] Getter implementation
  - [ ] Setter implementation
  - [ ] Custom accessor methods
- [ ] Memory management
  - [ ] ARC behavior
  - [ ] Retain/release patterns
  - [ ] Deallocation sequence

### 2.2 Categories
#### 2.2.1 Load Time Behavior
- [ ] Category loading
  - [ ] Load order determination
  - [ ] Method list merging
  - [ ] Property handling
- [ ] Initialization
  - [ ] +load vs +initialize
  - [ ] Category method order
  - [ ] Runtime integration
- [ ] Binary loading
  - [ ] Dynamic loading
  - [ ] Static linking
  - [ ] Load time optimization

#### 2.2.2 Method Collision Resolution
- [ ] Collision detection
  - [ ] Method name comparison
  - [ ] Implementation replacement
  - [ ] Original method preservation
- [ ] Category ordering
  - [ ] Build order effects
  - [ ] Link order significance
  - [ ] Runtime resolution
- [ ] Best practices
  - [ ] Naming conventions
  - [ ] Method prefixing
  - [ ] Documentation requirements
