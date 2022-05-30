project('Physics2D', 'cpp', version : '1.0')

physics2d_src = files(
  'PhysicsWorld.cpp',
  'PhysicsWorld_quadtree.cpp',
  'RigidBody.cpp',
  'colliders/CapsuleCollider.cpp',
  'colliders/CircleCollider.cpp',
  'colliders/Collider.cpp',
  'colliders/CollisionTests.cpp',
  'colliders/PolygonCollider.cpp',
  'colliders/RectangleCollider.cpp')
physics2d_inc = include_directories('include')

physics2d_lib = static_library('physics2d', 
  physics2d_src, 
  include_directories : physics2d_inc)

physics2d_dep = declare_dependency(
  include_directories : physics2d_inc,
  link_with : physics2d_lib)
