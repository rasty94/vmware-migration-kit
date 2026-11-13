# Graph Report - vmware-migration-kit  (2026-11-12)

## Corpus Check
- 23 files · ~71,573 words
- Verdict: corpus is large enough that graph structure adds value.

## Summary
- 1878 nodes · 2988 edges · 154 communities (122 shown, 32 thin omitted)
- Extraction: 97% EXTRACTED · 2% INFERRED · 0% AMBIGUOUS · INFERRED: 74 edges (avg confidence: 0.82)
- Token cost: 0 input · 0 output

## Community Hubs (Navigation)
- Nbdkit Runner (Go)
- VMware vCenter Client (Go)
- Volume State Tests
- Server Lifecycle Tests
- Volume Advanced Tests
- Heat Stack Abandon Module
- Ansible Utils and Disk Model
- Role Argument Specs
- Instance Creation Module
- Neutron Network Port Module
- Import Workloads Defaults
- Migration Variable Examples
- VMware Utilities and OS Detection
- Heat Wrap Stack Playbook
- Flavor Info Tests
- Python Pytest Fixtures
- Filesystem Utilities (Go)
- OpenStack Client Go Tests
- Convert Metadata Playbook
- AEE Image Build Workflow
- Builder Image Workflow
- Ansible Sanity CI
- Security Review Workflow
- Pre-migration Checks Playbook
- Cinder Volume Client (Go)
- Execution Environment Config
- Heat Abandon Playbook
- Gophercloud Volume Client
- Volume Import Playbook
- Conversion Host Migration Run
- Port Deletion Module
- Heat Template Generation
- Golang Lint CI
- Integration Test CI
- IP and Context Utilities
- Migrator Host Setup
- Flavor Matching Logic
- Ansible Lint CI
- Go Test CI
- Heat Stack Creation Module
- Galaxy Collection Metadata
- OpenVixDiskLib nbdkit Backend
- Certification Workflow
- Stable Tag Release Workflow
- Volume Basic Tests
- OpenStack Server Ops (Go)
- Volume Validation Tests
- Release Changelog Entries
- Galaxy Import Workflow
- Volume Stress Tests
- Volume Validation Async Checks
- Project Docs and Conventions
- Conversion Host Setup Playbook
- Volume Basic Test Setup
- Migration Workflow Concepts
- Heat and Metadata Concepts
- Localhost Inventory Example
- Cinder Volume Info (Go)
- Guest Metadata Gathering
- NIC Persistence Script
- Role Argument Main Spec
- Stress Server Tests
- Sanity Ignore Lists
- Flavor Import Module
- Conversion Host Role Meta
- Basic Test Auth Config
- Stress Test Auth Config
- Validation Test Auth Config
- Flavor Deletion Module
- Server Deletion Module
- Flavor Info Module
- Volume Info Module
- Pre-commit Hook Config
- Convert Metadata Role Meta
- Export Metadata Role Meta
- Import Workloads Role Meta
- Prelude Role Meta
- Basic Test Scaffolding
- Stress Test Scaffolding
- Validation Test Scaffolding
- Volume Test HTTP Requests
- Volume Deletion Module
- Cinder Volume Ops (Go)
- Volume Metadata Module
- Galaxy Collection Requirements
- Prelude Argument Specs
- Basic Test HTTP Requests
- Stress Test HTTP Requests
- Agent Build Guidelines
- nbdkit Release Concepts
- Conversion Host Option Specs
- CBT Sync Option Spec
- Cinder Volume Type Spec
- Credential Copy Option Spec
- Custom nbdkit Plugin Spec
- Cutover Option Spec
- Debug Option Spec
- Network Map Option Spec
- Tear Down Option Spec
- VMW Data Dir Option Spec
- Existing Flavor Option Spec
- Fixed IPs Option Spec
- Mapped Networks Option Spec
- vCenter Password Option Spec
- VDDK Libdir Option Spec
- VMs List Option Spec
- VMware Insecure Option Spec
- Server Test Payload
- Collection Requirements Spec
- Availability Zone Option Spec
- ESXi Host Option Spec
- Subnet UUID Option Spec
- Flavor UUID Option Spec
- Private Network Option Spec
- Security Groups Option Spec
- SSH Key Option Spec
- vCenter Hostname Option Spec
- vCenter Username Option Spec
- Stress Test URL Targets
- Subnet Validation Test
- Python Requirements Files
- OpenStack Module Doc Fragment
- Cleanup Script
- Prelude Script
- Basic Test Assertions
- Service Catalog Lookup
- Stress Test Assertions
- Validation Test Assertions
- Validation Volume Loop
- System Package Dependencies
- AEE Build Script
- Prelude Host Defaults
- Collection Build Script
- Changelog From Releases Script
- Changelog From Tags Script
- Go Module Definition
- Empty Requirements File

## God Nodes (most connected - your core abstractions)
1. `createMockProvider()` - 48 edges
2. `options` - 30 edges
3. `OpenstackAuth()` - 24 edges
4. `DstCloud` - 20 edges
5. `main()` - 16 edges
6. `VddkConfig` - 15 edges
7. `createFailingProvider()` - 15 edges
8. `tasks` - 14 edges
9. `tasks` - 14 edges
10. `fallbackRewriteAndDelete()` - 13 edges

## Surprising Connections (you probably didn't know these)
- `v2.1.5 Python Retrocompatibility Cleanup` --conceptually_related_to--> `Go Module Sources Flagged as Python Syntax and Invalid Extension`  [AMBIGUOUS]
  CHANGELOG.md → tests/sanity/ignore-2.20.txt
- `Go Module Sources Flagged as Python Syntax and Invalid Extension` --conceptually_related_to--> `v2.2.4 Binary Dispatcher Implementation`  [AMBIGUOUS]
  tests/sanity/ignore-2.20.txt → CHANGELOG.md
- `network_config.sh.j2 Template` --conceptually_related_to--> `v1.2.8 CBT Multi-disk and Socket Fixes`  [AMBIGUOUS]
  roles/import_workloads/templates/network_config.sh.j2 → CHANGELOG.md
- `Prelude Role as User-Customizable Pre-Migration Hook` --conceptually_related_to--> `v2.3.0 Custom nbdkit Plugin Bypassing VDDK`  [AMBIGUOUS]
  roles/prelude/README.md → CHANGELOG.md
- `TestRewriteKeepsCreateModeLogicalNames()` --calls--> `GenerateHeatTemplate()`  [EXTRACTED]
  tests/unit/abandon_heat_stack_test.go → plugins/modules/src/generate_heat_template/generate_heat_template.go

## Import Cycles
- None detected.

## Hyperedges (group relationships)
- **Sanity ignore files per ansible-core version** — tests_sanity_ignore_2_10, tests_sanity_ignore_2_15, tests_sanity_ignore_2_16, tests_sanity_ignore_2_17, tests_sanity_ignore_2_18, tests_sanity_ignore_2_19, tests_sanity_ignore_2_20 [EXTRACTED 1.00]
- **Python and system requirement files** — requirements, requirements_build, requirements_tests, aee_requirements, bindep, aee_bindep [EXTRACTED 1.00]

## Communities (154 total, 32 thin omitted)

### Community 0 - "Nbdkit Runner (Go)"
Cohesion: 0.05
Nodes (54): NbdkitServer, buildNbdCopyCommand(), buildV2VCommand(), findVirtV2v(), formatOptValue(), NbdkitConfig, newTestNbdkitConfig(), TestBuildNbdCopyCommand_EmptyOptions() (+46 more)

### Community 1 - "VMware vCenter Client (Go)"
Cohesion: 0.06
Nodes (24): MigrationConfig, CinderManageConfig, CheckVCenterConnectivity(), InitLogger(), AttachVolume(), GetInstanceUUID(), FindDevName(), GetDatastoreNameForDiskKey() (+16 more)

### Community 2 - "Volume State Tests"
Cohesion: 0.04
Nodes (46): msg, that, persist_vol_id, vol_read_1, vol_read_2, vol_read_3, body, body_format (+38 more)

### Community 3 - "Server Lifecycle Tests"
Cohesion: 0.04
Nodes (44): msg, that, body, body_format, method, return_content, status_code, url (+36 more)

### Community 4 - "Volume Advanced Tests"
Cohesion: 0.04
Nodes (44): msg, that, body, body_format, method, return_content, status_code, url (+36 more)

### Community 5 - "Heat Stack Abandon Module"
Cohesion: 0.10
Nodes (36): ResourceRef, Response, StackInfo, attachInfoFile(), cloneTemplate(), exitJson(), fallbackRewriteAndDelete(), hasExternalID() (+28 more)

### Community 6 - "Ansible Utils and Disk Model"
Cohesion: 0.09
Nodes (37): Disk, MigrateResponse, Response, ModuleArgs, Response, WrapVMData, DefaultIfEmpty(), ExitJson() (+29 more)

### Community 7 - "Role Argument Specs"
Cohesion: 0.05
Nodes (40): description, options, required, type, default, description, required, type (+32 more)

### Community 8 - "Instance Creation Module"
Cohesion: 0.11
Nodes (5): NicInfo, ModuleResponse, ServerArgs, VolOpts, success()

### Community 9 - "Neutron Network Port Module"
Cohesion: 0.08
Nodes (31): PortInfo, Response, CreatePort(), DeletePort(), GetNetwork(), GetPortsByDeviceID(), GetSubnetIDFromNetwork(), WaitForPortStatus() (+23 more)

### Community 10 - "Import Workloads Defaults"
Cohesion: 0.05
Nodes (36): import_workloads_boot_from_cinder, import_workloads_boot_script_path, import_workloads_cbt_sync, import_workloads_cinder_az, import_workloads_cinder_volume_type, import_workloads_converted, import_workloads_custom_nbdkit_plugin, import_workloads_cutover (+28 more)

### Community 11 - "Migration Variable Examples"
Cohesion: 0.06
Nodes (35): already_deploy_conversion_host, auth_url, password, project_id, project_name, user_domain_name, username, availability_zone (+27 more)

### Community 12 - "VMware Utilities and OS Detection"
Cohesion: 0.14
Nodes (32): DetectLinuxFromStrings(), DetectRhelCentosFromStrings(), DetectWindowsFromStrings(), ProcessUrl(), TestDetectLinuxFromStrings_CaseInsensitive(), TestDetectLinuxFromStrings_EmptyStrings(), TestDetectLinuxFromStrings_GenericLinux(), TestDetectLinuxFromStrings_LinuxInIdOnly() (+24 more)

### Community 13 - "Heat Wrap Stack Playbook"
Cohesion: 0.06
Nodes (34): fail_msg, that, msg, wrap_cloud, gather_facts, hosts, name, cloud (+26 more)

### Community 14 - "Flavor Info Tests"
Cohesion: 0.06
Nodes (33): msg, that, var, auth_url, password, project_domain_name, project_id, project_name (+25 more)

### Community 15 - "Python Pytest Fixtures"
Cohesion: 0.07
Nodes (8): VirtV2V, get_total_disk_capacity(), main(), run_module(), main(), virt_v2v_instance(), VirtV2V, TestVirtV2V

### Community 16 - "Filesystem Utilities (Go)"
Cohesion: 0.10
Nodes (26): FDevName(), GenRandom(), SafeVmName(), transliterate(), TestRunNbdKitFromLocal_Success(), writeFakeNbdkit(), TestFindDevName_BrokenSymlink(), TestFindDevName_EmptyDirectory() (+18 more)

### Community 17 - "OpenStack Client Go Tests"
Cohesion: 0.11
Nodes (28): DeleteFlavor(), DeleteServer(), GetFlavorInfo(), GetOSChangeID(), GetVolumeID(), UpdateVolumeMetadata(), createFailingProvider(), TestDeleteFlavorClientInitFailure() (+20 more)

### Community 18 - "Convert Metadata Playbook"
Cohesion: 0.07
Nodes (29): dest, mode, src, name, hosts, loop_var, name, cloud (+21 more)

### Community 19 - "AEE Image Build Workflow"
Cohesion: 0.07
Nodes (27): name, runs-on, steps, env, IMAGE_NAME, IMAGE_REGISTRY, IMAGE_TAG, QUAY_NAMESPACE (+19 more)

### Community 20 - "Builder Image Workflow"
Cohesion: 0.07
Nodes (27): name, runs-on, steps, env, IMAGE_NAME, IMAGE_REGISTRY, IMAGE_TAG, QUAY_NAMESPACE (+19 more)

### Community 21 - "Ansible Sanity CI"
Cohesion: 0.09
Nodes (26): jobs, sanity27, sanity3, python-version, name, on, pull_request, push (+18 more)

### Community 22 - "Security Review Workflow"
Cohesion: 0.07
Nodes (26): ANTHROPIC_VERTEX_PROJECT_ID, CLAUDE_CODE_USE_VERTEX, GOOGLE_APPLICATION_CREDENTIALS_JSON, jobs, security, name, on, pull_request (+18 more)

### Community 23 - "Pre-migration Checks Playbook"
Cohesion: 0.07
Nodes (26): msg, excludes, file_type, paths, recurse, go_modules, modules_root, path (+18 more)

### Community 24 - "Cinder Volume Client (Go)"
Cohesion: 0.13
Nodes (23): CreateVolume(), DeleteVolume(), IsVolumeConverted(), WaitForServerStatus(), WaitForVolumeStatus(), createMockProvider(), TestCreateVolumeFailure(), TestCreateVolumeSuccessBasic() (+15 more)

### Community 25 - "Execution Environment Config"
Cohesion: 0.09
Nodes (22): additional_build_files, dest, src, additional_build_steps, prepend_base, package_pip, package_pip, name (+14 more)

### Community 26 - "Heat Abandon Playbook"
Cohesion: 0.09
Nodes (22): fail_msg, that, msg, abandon_cloud, gather_facts, hosts, name, cloud (+14 more)

### Community 27 - "Gophercloud Volume Client"
Cohesion: 0.14
Nodes (19): VolumeAttachment, WrapVM, DiscoverWrapVM(), discoverWrapVMFromServer(), DiscoverWrapVMs(), GetServer(), GetServerByName(), GetServerVolumeAttachments() (+11 more)

### Community 28 - "Volume Import Playbook"
Cohesion: 0.10
Nodes (19): name, become, hosts, loop_var, name, tasks, ansible.builtin.include_role, loop (+11 more)

### Community 29 - "Conversion Host Migration Run"
Cohesion: 0.10
Nodes (19): name, merged_vm_data, become, hosts, loop_var, name, tasks, ansible.builtin.include_role (+11 more)

### Community 30 - "Port Deletion Module"
Cohesion: 0.15
Nodes (18): ModuleArgs, ModuleArgs, ModuleArgs, ModuleArgs, ModuleArgs, ModuleArgs, Response, ModuleArgs (+10 more)

### Community 31 - "Heat Template Generation"
Cohesion: 0.23
Nodes (16): ModuleArgs, Response, VMData, exitJson(), GenerateHeatTemplate(), GenerateWrapHeatTemplate(), Run(), sanitizeName() (+8 more)

### Community 32 - "Golang Lint CI"
Cohesion: 0.11
Nodes (18): name, runs-on, steps, jobs, build, name, on, pull_request (+10 more)

### Community 33 - "Integration Test CI"
Cohesion: 0.11
Nodes (18): name, runs-on, steps, timeout-minutes, jobs, integration, name, on (+10 more)

### Community 34 - "IP and Context Utilities"
Cohesion: 0.18
Nodes (7): ModuleArgs, VolumeTypeMapping, FixedIPsForNeutron(), TestFixedIPsForNeutron_Empty(), TestFixedIPsForNeutron_InvalidSkipped(), TestFixedIPsForNeutron_IPv4AndIPv6Mixed(), TestFixedIPsForNeutron_OnlyLinkLocalV6()

### Community 35 - "Migrator Host Setup"
Cohesion: 0.11
Nodes (17): dest, mode, src, name, state, use_backend, name, hosts (+9 more)

### Community 36 - "Flavor Matching Logic"
Cohesion: 0.24
Nodes (13): Disk, DiskInfo, GuestInfo, Response, ExitJson(), FailJson(), FailWithMessage(), findBestMatchingFlavor() (+5 more)

### Community 37 - "Ansible Lint CI"
Cohesion: 0.12
Nodes (16): name, runs-on, steps, jobs, build, name, on, pull_request (+8 more)

### Community 38 - "Go Test CI"
Cohesion: 0.12
Nodes (16): name, runs-on, steps, jobs, build, name, on, pull_request (+8 more)

### Community 39 - "Heat Stack Creation Module"
Cohesion: 0.21
Nodes (12): Response, StackInfo, exitJson(), Run(), StackCreateDecision(), WriteStackInfoFile(), TestModuleArgsUnmarshalDisableRollback(), TestModuleArgsUnmarshalOutputDir() (+4 more)

### Community 40 - "Galaxy Collection Metadata"
Cohesion: 0.12
Nodes (15): authors, build_ignore, dependencies, vmware.vmware, vmware.vmware_rest, description, homepage, issues (+7 more)

### Community 42 - "Certification Workflow"
Cohesion: 0.14
Nodes (13): uses, concurrency, cancel-in-progress, group, jobs, call, name, on (+5 more)

### Community 43 - "Stable Tag Release Workflow"
Cohesion: 0.14
Nodes (13): jobs, move-stable, runs-on, steps, name, on, push, tags (+5 more)

### Community 44 - "Volume Basic Tests"
Cohesion: 0.14
Nodes (14): body, identity, scope, auth, network, port, volume, volumeAttachment (+6 more)

### Community 45 - "OpenStack Server Ops (Go)"
Cohesion: 0.15
Nodes (12): CreateServer(), DetachVolume(), OpenstackAuth(), activeServerForVolume(), Run(), TestCreateServerAPIFailure(), TestCreateServerClientInitFailure(), TestCreateServerSuccess() (+4 more)

### Community 46 - "Volume Validation Tests"
Cohesion: 0.15
Nodes (13): body, network, port, server, volume, name, network_id, flavorRef (+5 more)

### Community 47 - "Release Changelog Entries"
Cohesion: 0.21
Nodes (10): v1.0.0 Initial VMware to OpenStack Release, v1.2.8 CBT Multi-disk and Socket Fixes, v2.0.0 Collection Path Refactoring, v2.0.6 Gophercloud Replaces openstack.cloud Modules, v2.2.1 AGENTS.md Added for AI Agent Guidelines, v2.2.4 Binary Dispatcher Implementation, v2.2.6 Claude Security Review Workflow, network_config.sh.j2 Template (+2 more)

### Community 48 - "Galaxy Import Workflow"
Cohesion: 0.17
Nodes (11): name, permissions, uses, jobs, import-galaxy, name, on, pull_request (+3 more)

### Community 49 - "Volume Stress Tests"
Cohesion: 0.17
Nodes (12): jid, tasks, ansible.builtin.async_status, ansible.builtin.include_tasks, async, delay, failed_when, name (+4 more)

### Community 50 - "Volume Validation Async Checks"
Cohesion: 0.17
Nodes (12): jid, tasks, ansible.builtin.async_status, ansible.builtin.include_tasks, async, delay, failed_when, name (+4 more)

### Community 51 - "Project Docs and Conventions"
Cohesion: 0.22
Nodes (6): Version Management (galaxy.yml as source of truth), Adding a New Golang Module Procedure, Known Limitations (BTRFS, Support Scope), Local NFS Migration Workflow, Migration Workflows (NBDKit, Virt-v2v, Local NFS), Ansible Collection Plugin Type Directory Layout

### Community 52 - "Conversion Host Setup Playbook"
Cohesion: 0.18
Nodes (10): name, hosts, name, tasks, ansible.builtin.include_role, name, vars, when (+2 more)

### Community 53 - "Volume Basic Test Setup"
Cohesion: 0.18
Nodes (11): name, size, tasks, ansible.builtin.include_tasks, delay, failed_when, loop, name (+3 more)

### Community 54 - "Migration Workflow Concepts"
Cohesion: 0.20
Nodes (10): CBT Two-Phase Migration, NBDKit Migration Workflow, Conversion Host Network Requirements, Virt-v2v Migration Workflow, Cinder Volume Migration Metadata, Migration Conversion Host Requirements, OpenVixDiskLib nbdkit Backend, Migration Use Cases (+2 more)

### Community 55 - "Heat and Metadata Concepts"
Cohesion: 0.22
Nodes (6): v2.3.0 Heat Stack Wrapping With Abandon Rollback, VMware vCenter ACL Requirements, import_workloads.json.j2 Template, Generated Import Workloads Config (OpenStack and Migration Settings), Heat Stack Wrap and Abandon Playbooks, TLS Certificate Verification Settings (vmware_insecure, openstack_insecure)

### Community 56 - "Localhost Inventory Example"
Cohesion: 0.20
Nodes (9): ansible_ssh_private_key_file, ansible_ssh_user, conversion_host, hosts, conv_host_ip, localhost, ansible_connection, migrator (+1 more)

### Community 57 - "Cinder Volume Info (Go)"
Cohesion: 0.20
Nodes (10): VolumeInfo, GetVolumeInfo(), GetVolumeInfoByID(), TestGetVolumeInfoByIDClientInitFailure(), TestGetVolumeInfoByIDNotFound(), TestGetVolumeInfoByIDSuccess(), TestGetVolumeInfoClientInitFailure(), TestGetVolumeInfoMultipleFound() (+2 more)

### Community 58 - "Guest Metadata Gathering"
Cohesion: 0.20
Nodes (9): name, hosts, loop_var, name, tasks, ansible.builtin.include_role, loop, loop_control (+1 more)

### Community 59 - "NIC Persistence Script"
Cohesion: 0.36
Nodes (8): extract_ifconfig(), extract_netplan_connections(), extract_nm_connections(), extract_sysconfig_connections(), generate_udev_rules(), log(), main(), network_config.sh script

### Community 60 - "Role Argument Main Spec"
Cohesion: 0.20
Nodes (9): argument_specs, main, description, options, short_description, vcenter_datacenter, description, required (+1 more)

### Community 61 - "Stress Server Tests"
Cohesion: 0.20
Nodes (10): body, network, server, volumeAttachment, name, flavorRef, imageRef, name (+2 more)

### Community 63 - "Flavor Import Module"
Cohesion: 0.33
Nodes (6): CreatedFlavor, FlavorResource, ModuleResponse, fail(), Run(), success()

### Community 64 - "Conversion Host Role Meta"
Cohesion: 0.22
Nodes (8): dependencies, role, galaxy_info, author, description, galaxy_tags, license, min_ansible_version

### Community 65 - "Basic Test Auth Config"
Cohesion: 0.22
Nodes (9): auth_url, password, project_domain_name, project_id, project_name, region_name, user_domain_name, username (+1 more)

### Community 66 - "Stress Test Auth Config"
Cohesion: 0.22
Nodes (9): auth_url, password, project_domain_name, project_id, project_name, region_name, user_domain_name, username (+1 more)

### Community 67 - "Validation Test Auth Config"
Cohesion: 0.22
Nodes (9): auth_url, password, project_domain_name, project_id, project_name, region_name, user_domain_name, username (+1 more)

### Community 68 - "Flavor Deletion Module"
Cohesion: 0.54
Nodes (7): ModuleArgs, Response, ExitJson(), FailJson(), FailWithMessage(), returnResponse(), Run()

### Community 69 - "Server Deletion Module"
Cohesion: 0.54
Nodes (7): ModuleArgs, Response, ExitJson(), FailJson(), FailWithMessage(), returnResponse(), Run()

### Community 70 - "Flavor Info Module"
Cohesion: 0.54
Nodes (7): ModuleArgs, Response, ExitJson(), FailJson(), FailWithMessage(), returnResponse(), Run()

### Community 71 - "Volume Info Module"
Cohesion: 0.57
Nodes (7): ExitJson(), FailJson(), FailWithMessage(), returnResponse(), Run(), Response, VolumeInfo

### Community 72 - "Pre-commit Hook Config"
Cohesion: 0.25
Nodes (7): exclude, id, language_version, repos, hooks, repo, rev

### Community 73 - "Convert Metadata Role Meta"
Cohesion: 0.25
Nodes (7): dependencies, galaxy_info, author, description, galaxy_tags, license, min_ansible_version

### Community 74 - "Export Metadata Role Meta"
Cohesion: 0.25
Nodes (7): dependencies, galaxy_info, author, description, galaxy_tags, license, min_ansible_version

### Community 75 - "Import Workloads Role Meta"
Cohesion: 0.25
Nodes (7): dependencies, galaxy_info, author, description, galaxy_tags, license, min_ansible_version

### Community 76 - "Prelude Role Meta"
Cohesion: 0.25
Nodes (7): dependencies, galaxy_info, author, description, galaxy_tags, license, min_ansible_version

### Community 77 - "Basic Test Scaffolding"
Cohesion: 0.25
Nodes (7): gather_facts, hosts, name, vars, cloud_config, fake_os_url, server_pid_file

### Community 78 - "Stress Test Scaffolding"
Cohesion: 0.25
Nodes (7): gather_facts, hosts, name, vars, cloud_config, fake_os_url, server_pid_file

### Community 79 - "Validation Test Scaffolding"
Cohesion: 0.25
Nodes (7): gather_facts, hosts, name, vars, cloud_config, fake_os_url, server_pid_file

### Community 80 - "Volume Test HTTP Requests"
Cohesion: 0.25
Nodes (8): body_format, headers, method, return_content, status_code, url, Content-Type, ansible.builtin.uri

### Community 81 - "Volume Deletion Module"
Cohesion: 0.67
Nodes (6): Response, ExitJson(), FailJson(), FailWithMessage(), returnResponse(), Run()

### Community 82 - "Cinder Volume Ops (Go)"
Cohesion: 0.33
Nodes (6): CinderManage(), GetVolume(), TestCinderManageSuccess(), TestGetVolumeClientInitFailure(), TestGetVolumeNotFound(), TestGetVolumeSuccess()

### Community 83 - "Volume Metadata Module"
Cohesion: 0.67
Nodes (6): ExitJson(), FailJson(), FailWithMessage(), returnResponse(), Run(), Response

### Community 84 - "Galaxy Collection Requirements"
Cohesion: 0.33
Nodes (5): collections, name, source, type, version

### Community 85 - "Prelude Argument Specs"
Cohesion: 0.33
Nodes (6): prelude_host_entries, default, description, elements, required, type

### Community 86 - "Basic Test HTTP Requests"
Cohesion: 0.33
Nodes (6): body_format, method, return_content, status_code, url, ansible.builtin.uri

### Community 87 - "Stress Test HTTP Requests"
Cohesion: 0.33
Nodes (6): body_format, method, return_content, status_code, url, ansible.builtin.uri

### Community 88 - "Agent Build Guidelines"
Cohesion: 0.40
Nodes (3): Containerized Build Process, Go Ansible Module Pattern, Python Thin Wrapper Modules

### Community 90 - "Conversion Host Option Specs"
Cohesion: 0.40
Nodes (5): default, description, required, type, already_deploy_conversion_host

### Community 91 - "CBT Sync Option Spec"
Cohesion: 0.40
Nodes (5): default, description, required, type, cbt_sync

### Community 92 - "Cinder Volume Type Spec"
Cohesion: 0.40
Nodes (5): default, description, required, type, cinder_volume_type

### Community 93 - "Credential Copy Option Spec"
Cohesion: 0.40
Nodes (5): default, description, required, type, copy_openstack_credentials_to_conv_host

### Community 94 - "Custom nbdkit Plugin Spec"
Cohesion: 0.40
Nodes (5): default, description, required, type, custom_nbdkit_plugin

### Community 95 - "Cutover Option Spec"
Cohesion: 0.40
Nodes (5): default, description, required, type, cutover

### Community 96 - "Debug Option Spec"
Cohesion: 0.40
Nodes (5): default, description, required, type, debug

### Community 97 - "Network Map Option Spec"
Cohesion: 0.40
Nodes (5): default, description, required, type, network_map

### Community 98 - "Tear Down Option Spec"
Cohesion: 0.40
Nodes (5): os_migrate_tear_down, default, description, required, type

### Community 99 - "VMW Data Dir Option Spec"
Cohesion: 0.40
Nodes (5): os_migrate_vmw_data_dir, default, description, required, type

### Community 100 - "Existing Flavor Option Spec"
Cohesion: 0.40
Nodes (5): use_existing_flavor, default, description, required, type

### Community 101 - "Fixed IPs Option Spec"
Cohesion: 0.40
Nodes (5): use_fixed_ips, default, description, required, type

### Community 102 - "Mapped Networks Option Spec"
Cohesion: 0.40
Nodes (5): used_mapped_networks, default, description, required, type

### Community 103 - "vCenter Password Option Spec"
Cohesion: 0.40
Nodes (5): vcenter_password, description, no_log, required, type

### Community 104 - "VDDK Libdir Option Spec"
Cohesion: 0.40
Nodes (5): vddk_libdir, default, description, required, type

### Community 105 - "VMs List Option Spec"
Cohesion: 0.40
Nodes (5): vms_list, description, elements, required, type

### Community 106 - "VMware Insecure Option Spec"
Cohesion: 0.40
Nodes (5): vmware_insecure, default, description, required, type

### Community 107 - "Server Test Payload"
Cohesion: 0.40
Nodes (5): server, flavorRef, imageRef, name, networks

### Community 108 - "Collection Requirements Spec"
Cohesion: 0.50
Nodes (3): collections, name, version

### Community 109 - "Availability Zone Option Spec"
Cohesion: 0.50
Nodes (4): description, required, type, availability_zone

### Community 110 - "ESXi Host Option Spec"
Cohesion: 0.50
Nodes (4): description, required, type, esxi_hostname

### Community 111 - "Subnet UUID Option Spec"
Cohesion: 0.50
Nodes (4): description, required, type, export_metadata_subnet_uuid

### Community 112 - "Flavor UUID Option Spec"
Cohesion: 0.50
Nodes (4): description, required, type, flavor_uuid

### Community 113 - "Private Network Option Spec"
Cohesion: 0.50
Nodes (4): description, required, type, openstack_private_network

### Community 114 - "Security Groups Option Spec"
Cohesion: 0.50
Nodes (4): security_groups, description, required, type

### Community 115 - "SSH Key Option Spec"
Cohesion: 0.50
Nodes (4): ssh_key_name, description, required, type

### Community 116 - "vCenter Hostname Option Spec"
Cohesion: 0.50
Nodes (4): vcenter_hostname, description, required, type

### Community 117 - "vCenter Username Option Spec"
Cohesion: 0.50
Nodes (4): vcenter_username, description, required, type

### Community 118 - "Stress Test URL Targets"
Cohesion: 0.50
Nodes (4): body, name, url, loop

### Community 119 - "Subnet Validation Test"
Cohesion: 0.50
Nodes (4): subnet, cidr, ip_version, network_id

### Community 124 - "Basic Test Assertions"
Cohesion: 0.67
Nodes (3): msg, that, ansible.builtin.assert

### Community 125 - "Service Catalog Lookup"
Cohesion: 0.67
Nodes (3): found_server_id, service_catalog, ansible.builtin.set_fact

### Community 126 - "Stress Test Assertions"
Cohesion: 0.67
Nodes (3): msg, that, ansible.builtin.assert

### Community 127 - "Validation Test Assertions"
Cohesion: 0.67
Nodes (3): msg, that, ansible.builtin.assert

### Community 128 - "Validation Volume Loop"
Cohesion: 0.67
Nodes (3): name, size, loop

## Ambiguous Edges - Review These
- `requirements.yml` → `v2.2.4 Binary Dispatcher Implementation`  [AMBIGUOUS]
  CHANGELOG.md · relation: conceptually_related_to
- `Version Management (galaxy.yml as source of truth)` → `Galaxy.yml and CHANGELOG Version Sync Rule`  [AMBIGUOUS]
  AGENTS.md · relation: conceptually_related_to
- `v1.2.8 CBT Multi-disk and Socket Fixes` → `network_config.sh.j2 Template`  [AMBIGUOUS]
  roles/import_workloads/templates/network_config.sh.j2 · relation: conceptually_related_to
- `v2.1.5 Python Retrocompatibility Cleanup` → `Go Module Sources Flagged as Python Syntax and Invalid Extension`  [AMBIGUOUS]
  CHANGELOG.md · relation: conceptually_related_to
- `v2.2.4 Binary Dispatcher Implementation` → `Go Module Sources Flagged as Python Syntax and Invalid Extension`  [AMBIGUOUS]
  tests/sanity/ignore-2.20.txt · relation: conceptually_related_to
- `v2.3.0 Custom nbdkit Plugin Bypassing VDDK` → `Prelude Role as User-Customizable Pre-Migration Hook`  [AMBIGUOUS]
  roles/prelude/README.md · relation: conceptually_related_to

## Knowledge Gaps
- **15 isolated node(s):** `vmware-migration-kit`, `Version Management (galaxy.yml as source of truth)`, `Conversion Host Network Requirements`, `Virt-v2v Migration Workflow`, `Cinder Volume Migration Metadata` (+10 more)
  These have ≤1 connection - possible missing edges or undocumented components. (Counts symbols only; 923 node(s) total have ≤1 connection when file, concept and rationale nodes are included.)
- **32 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `OpenstackAuth()` connect `OpenStack Server Ops (Go)` to `VMware vCenter Client (Go)`, `Flavor Matching Logic`, `Heat Stack Abandon Module`, `Flavor Deletion Module`, `Heat Stack Creation Module`, `Instance Creation Module`, `Neutron Network Port Module`, `Server Deletion Module`, `Ansible Utils and Disk Model`, `Flavor Info Module`, `Volume Info Module`, `Volume Deletion Module`, `Volume Metadata Module`, `Gophercloud Volume Client`, `Port Deletion Module`, `Flavor Import Module`?**
  _High betweenness centrality (0.005) - this node is a cross-community bridge._
- **What connects `vmware-migration-kit`, `Version Management (galaxy.yml as source of truth)`, `Conversion Host Network Requirements` to the rest of the system?**
  _15 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `Nbdkit Runner (Go)` be split into smaller, more focused modules?**
  _Cohesion score 0.05201266395296246 - nodes in this community are weakly interconnected._
- **Why does `options` connect `Role Argument Main Spec` to `Role Argument Specs`, `Prelude Argument Specs`, `Conversion Host Option Specs`, `CBT Sync Option Spec`, `Cinder Volume Type Spec`, `Credential Copy Option Spec`, `Custom nbdkit Plugin Spec`, `Cutover Option Spec`, `Debug Option Spec`, `Network Map Option Spec`, `Tear Down Option Spec`, `VMW Data Dir Option Spec`, `Existing Flavor Option Spec`, `Fixed IPs Option Spec`, `Mapped Networks Option Spec`, `vCenter Password Option Spec`, `VDDK Libdir Option Spec`, `VMs List Option Spec`, `VMware Insecure Option Spec`, `Availability Zone Option Spec`, `ESXi Host Option Spec`, `Subnet UUID Option Spec`, `Flavor UUID Option Spec`, `Private Network Option Spec`, `Security Groups Option Spec`, `SSH Key Option Spec`, `vCenter Hostname Option Spec`, `vCenter Username Option Spec`?**
  _High betweenness centrality (0.005) - this node is a cross-community bridge._
- **Should `VMware vCenter Client (Go)` be split into smaller, more focused modules?**
  _Cohesion score 0.06493506493506493 - nodes in this community are weakly interconnected._

### Low-confidence Hints
_AMBIGUOUS edges — the extractor was unsure. Verify before acting on these._

- **What is the exact relationship between `requirements.yml` and `v2.2.4 Binary Dispatcher Implementation`?**
  _Edge tagged AMBIGUOUS (relation: conceptually_related_to) - confidence is low._
- **What is the exact relationship between `Version Management (galaxy.yml as source of truth)` and `Galaxy.yml and CHANGELOG Version Sync Rule`?**
  _Edge tagged AMBIGUOUS (relation: conceptually_related_to) - confidence is low._