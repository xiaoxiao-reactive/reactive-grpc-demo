Reactive-gPRC-demo
===================

Integrates reactive programming with grpc-java.

### Development Flow

* Write your protobuf IDL
* Compile protobuf:  'mvn protobuf:compile'
* Implement reactive service with Reactor Grpc classes
* 
```
public class ReactiveGreeterImpl extends ReactorGreeterGrpc.GreeterImplBase {
}
```

* Build project: 'mvn -DskipTests clean package'


### References

* https://github.com/salesforce/reactive-grpc