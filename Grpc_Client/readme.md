The gRPC client project requires the following NuGet packages:

- `Grpc.Net.Client`, which contains the .NET Core client.
- `Google.Protobuf`, which contains protobuf message APIs for C#.
- `Grpc.Tools`, which contain C# tooling support for protobuf files. The tooling package isn't required at runtime, so the dependency is marked with PrivateAssets="All".