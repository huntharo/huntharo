## Hi there 👋

I'm Harold, a software engineer focused on building high-performance distributed systems.

### Featured Projects

#### 🔄 [p-map-iterable](https://github.com/shutterstock/p-map-iterable)
A TypeScript library for efficient async iteration with backpressure control
- Built on concepts from p-map and p-queue
- Optimizes throughput for async read/write operations
- Prevents producer/consumer racing through backpressure

#### 🗺️ [streaming-sitemaps](https://github.com/shutterstock/streaming-sitemaps)
Generate XML sitemaps at scale from streaming data
- Process hundreds of millions of items efficiently
- Integrates with Kafka/Kinesis streams
- Outputs to S3 with DynamoDB backing

#### ⚡ [lambda-dispatch](https://github.com/pwrdrvr/lambda-dispatch)
Advanced request routing for AWS Lambda in Rust and .NET
- Eliminates cold starts
- Enables concurrent request handling
- Allows for streaming request and response bodies (although this is troublesome with ALBs)
- ~5ms faster response times than standard Lambda
- Includes CDK constructs for easy deployment

#### 🚀 [microapps-core](https://github.com/pwrdrvr/microapps-core)
Next.js multi-version deployment framework
- Run unlimited versions on a single URL
- Share host between multiple apps
- Smoke test new versions before user exposure
- Seamless version transitions without page reloads
- Includes CDK deployment constructs