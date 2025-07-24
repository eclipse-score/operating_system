..
   # *******************************************************************************
   # Copyright (c) 2024 Contributors to the Eclipse Foundation
   #
   # See the NOTICE file(s) distributed with this work for additional
   # information regarding copyright ownership.
   #
   # This program and the accompanying materials are made available under the
   # terms of the Apache License Version 2.0 which is available at
   # https://www.apache.org/licenses/LICENSE-2.0
   #
   # SPDX-License-Identifier: Apache-2.0
   # *******************************************************************************

Component Requirements for Operating System
===========================================

.. comp_req:: ACL Support
   :id: comp_req__operating_system__acl
   :reqtype: Functional
   :security: YES
   :safety: ASIL_B
   :status: valid
   :satisfies: aou_req__baselibs__acl

   The OS shall offer mechanisms for authorized operating system object access on a per process basis. In the case of Linux, POSIX 1003.1E Draft17 ACL is the preferred solution.
