junit_tests(
  name='scala',
  dependencies=[
    'finatra/inject/inject-app:test-deps',
    'finatra/inject/inject-core:test-deps',
    'finatra/inject/inject-server:test-deps',
    'finatra/thrift:test-deps',
    'finatra/examples/thrift-server/thrift-example-idl',
    'finatra/examples/thrift-server/thrift-example-server',
  ],
  sources=rglobs('*.scala'),
  resources=[
    'finatra/examples/thrift-server/thrift-example-server/src/test/resources',
  ]
)