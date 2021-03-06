---
title: Cloud Foundry Documentation
---

<h1>Overview</h1>
Welcome to the Cloud Foundry documentation.
<hr />
<div>
<div class="column-left">
  <div class="column-title">
      <h4>Using Cloud Foundry</h4>
  </div>
  <p><i>Push applications to Cloud Foundry</i></p>
  <hr />
  <p>
    Deploying Applications<br />
    <a href="/devguide/deploy-apps/prepare-to-deploy.html">App Design for the Cloud</a><br />
    <a href="/devguide/deploy-apps/">Push Your Application</a><br />
    <a href="/devguide/services/">Using Services</a><br />
    <a href="/devguide/services/migrate-db.html">Migrating a Database in Cloud Foundry</a><br />
    <a href="/devguide/deploy-apps/environment-variable.html">Using Environment Variables</a><br />
    <a href="/devguide/deploy-apps/domains-routes.html">Mapping a Custom Domain</a>
    <a href="/running/cf-api-endpoint.html">Identifying the API Endpoint for your Cloud Foundry Instance</a>
  </p>
  <hr />
  <p>
    Managing and Troubleshooting<br />
    <a href="/devguide/deploy-apps/manifest.html">Application Manifests (manifest.yml)</a><br />
    <a href="/devguide/deploy-apps/streaming-logs.html">Application Logging</a><br />
    <a href="/devguide/services/log-management.html">Using Third-Party Log Management Services</a><br />
    <a href="/devguide/services/log-management-thirdparty-svc.html">Configuring Selected Third-Party Log Management Services</a><br />
    <a href="/devguide/services/integrate-splunk.html">Integrating Cloud Foundry with Splunk</a><br />
    <a href="/devguide/deploy-apps/troubleshoot-app-health.html">Application Troubleshooting</a>
  </p>
  <hr />
  <p>Client Tools<br />
    <a href="/devguide/installcf/">The cf Command Line Tool</a><br />
    <a href="/devguide/installcf/use-cli-plugins.html">Using cf CLI Plugins</a><br />
    <a href="/devguide/deploy-apps/cf-scale.html">Scaling an Application Using cf scale</a><br />
    <a href="/buildpacks/java/sts.html">Eclipse Plugin</a><br />
    <a href="/buildpacks/java/build-tool-int.html">Build Tool Integration</a>
  </p>
</div>

<div class="column-middle">
  <div class="column-title">
    <h4>Extending Cloud Foundry</h4>
  </div>
  <p><i>Extension points in Cloud Foundry</i></p>
  <hr />
  <p>
    Custom Services<br />
    <a href="/services/overview.html">Overview</a><br />
    <a href="/services/api.html">Service Broker API</a><br />
    <a href="/services/managing-service-brokers.html">Managing Service Brokers</a><br />
    <a href="/services/access-control.html">Access Control</a><br />
    <a href="/services/catalog-metadata.html">Catalog Metadata</a><br />
    <a href="/services/binding-credentials.html">Binding Credentials</a><br />
    <a href="/services/dashboard-sso.html">Dashboard Single Sign-On</a><br />
    <a href="/services/examples.html">Example Service Brokers</a>
 </p>

  <hr />
  <p>
    Buildpacks<br />
	<a href="/buildpacks/">Buildpacks</a><br />
	<a href="/buildpacks/detection.html">Buildpack Detection</a><br />
	<a href="/buildpacks/custom.html">Custom Buildpacks</a><br />
	<a href="/buildpacks/depend-pkg-offline.html">Packaging Dependencies for Offline Buildpacks</a><br />
  </p>
  <p>
	<a href="/buildpacks/java/">Java Buildpack</a><br />
	<a href="/buildpacks/java/gsg-grails.html">Getting Started Deploying Grails Apps</a><br />
	<a href="/buildpacks/java/gsg-ratpack.html">Getting Started Deploying Ratpack Apps</a><br />
	<a href="/buildpacks/java/gsg-spring.html">Getting Started Deploying Spring Apps</a><br />
	<a href="/buildpacks/java/java-tips.html">Tips for Java Developers</a><br />
	<a href="/buildpacks/java/grails-service-bindings.html">Grails Service Connections</a><br />
	<a href="/buildpacks/java/spring-service-bindings.html">Spring Service Connections</a><br />
	<a href="/buildpacks/java/play-service-bindings.html">Play Framework Service Connections</a><br />
  </p>
  <p>
	<a href="/buildpacks/node">Node.js Buildpack</a><br />
	<a href="/buildpacks/node/node-tips.html">Tips for Node.js Developers</a><br />
	<a href="/buildpacks/node/node-service-bindings.html">Node.js Service Connections</a><br />
  </p>
  <p>
	<a href="/buildpacks/ruby/">Ruby Buildpack</a><br />
	<a href="/buildpacks/ruby/gsg-ror.html">Getting Started Deploying Ruby on Rails Apps</a><br />
	<a href="/buildpacks/ruby/ruby-tips.html">Tips for Ruby Developers</a><br />
	<a href="/buildpacks/ruby/ruby-service-bindings.html">Ruby Service Connections</a><br />
  </p>
</div>

<div class="column-right">
  <div class="column-title">
      <h4>Running Cloud Foundry</h4>
  </div>
  <p><i>Manage your Cloud Foundry deployment</i></p>
  <hr />
  <p>
    Cloud Foundry Concepts<br />
	<a href="/concepts/overview.html">Overview</a><br />
    <a href="/concepts/architecture/">Cloud Foundry Components</a><br />
    <a href="/concepts/how-applications-are-staged.html">How Applications Are Staged</a><br />
    <a href="/concepts/high-availability.html">Scaling Cloud Foundry</a><br />
	<a href="/concepts/roles.html">Orgs, Spaces, Roles, and Permissions</a><br />
	<a href="/concepts/stacks.html">Stacks</a><br />
    <a href="/concepts/security.html">Cloud Foundry Security</a></p>
  </p>
  <hr />
  <p>BOSH<br />
  <a href="/bosh/">BOSH Documentation</a><br />
  </p>
  <p>
    BOSH Foundations<br />
    <a href="/bosh/terminology.html">BOSH Terminology</a><br />
    <a href="/bosh/understanding-bosh.html">Understanding BOSH</a><br />
    <a href="/bosh/bosh-components.html">BOSH Components</a><br />
    <a href="/bosh/jobs.html">BOSH Jobs and Errands</a><br />
    <a href="/bosh/workflow.html">Basic BOSH Workflow</a><br />
    <a href="/bosh/design.html">BOSH Design Principles</a><br />
  </p>
  <p>
    Working with BOSH<br />
    <a href="/bosh/bosh-cli.html">BOSH CLI</a><br />
    <a href="/bosh/setup-aws.html">Setting Up AWS for BOSH</a><br />
    <a href="/bosh/setup-openstack.html">Setting Up OpenStack for BOSH</a><br />
    <a href="/bosh/setup-vsphere.html">Setting Up vSphere for BOSH</a><br />
    <a href="/bosh/deploy-microbosh.html">Deploying MicroBOSH</a><br />
    <a href="/bosh/deploy-microbosh-to-aws.html">Deploying MicroBOSH to AWS</a><br />
    <a href="/bosh/deploy-microbosh-to-openstack.html">Deploying MicroBOSH to OpenStack</a><br />
    <a href="/bosh/deploy-with-bosh.html">Deploying Distributed Software with BOSH</a><br />
  </p>
  <p>
    BOSH in Depth<br />
    <a href="/bosh/create-release.html">Creating a BOSH Release</a><br />
	<a href="/bosh/packages.html">Creating BOSH Packages</a><br />
    <a href="/bosh/deployment-manifest.html">Understanding the BOSH Deployment Manifest</a><br />
    <a href="/bosh/sample-manifest.html">Sample BOSH Deployment Manifest</a><br />
    <a href="/bosh/create-micro-manifest.html">Creating a MicroBOSH Deployment Manifest</a><br />
    <a href="/bosh/job-logs.html">Using BOSH Job and Errand Logs</a><br />
	<a href="/bosh/bosh-resurrector.html">Using the BOSH Resurrector</a><br />
	<a href="/bosh/sysadmin-commands.html">BOSH Commands for System Administration</a><br />
	<a href="/bosh/disaster-recovery.html">Disaster Recovery with BOSH</a><br />
	<a href="/bosh/snapshots.html">Using BOSH Snapshots with Your IaaS</a><br />
	<a href="/bosh/connect-postgres-hadb.html">Connecting BOSH or MicroBOSH to an External Postgres Database</a><br />
	<a href="/bosh/drain-scripts.html">Drain Scripts</a><br />
	<a href="/bosh/persistent-disks.html">Persistent Disks</a><br />
	<a href="/bosh/vm-anti-affinity.html">VM Anti-affinity</a><br />
 </p>
  <hr />
  <p>
    Deploy Cloud Foundry<br />
    <a href="/deploying/">Overview</a><br />
    <a href="/deploying/ec2/">Deploy to AWS</a><br />
	<a href="/deploying/ec2/bootstrap-aws-vpc.html">
		Deploying to AWS with BOSH AWS Bootstrap</a></br>
	<a href="/deploying/ec2/aws_steps.html">Deploying to AWS Tutorial</a></br>
    <a href="/deploying/openstack/">Deploy to OpenStack</a><br />
    <a href="/deploying/vsphere/">Deploy to vSphere</a><br />
    <a href="/deploying/vcloud/">Deploy to vCloud Air or vCloud Director</a><br />
    <a href="/deploying/adding-services.html">Deploying Community Services</a><br />
    <a href="/deploying/run-local.html">Run a Local Cloud Foundry Instance</a>
    <a href="/deploying/cf-manifest-spiff.html">Generating a Cloud Foundry Deployment Manifest Using Spiff</a>
    <a href="/deploying/cf-stub-aws.html">Customizing the Cloud Foundry Deployment Manifest Stub for AWS</a>
    <a href="/deploying/cf-stub-vcloud.html">Customizing the Cloud Foundry Deployment Manifest Stub for vCloud</a>

  </p>
  <hr />
  <p>
    Run Cloud Foundry<br />
    <a href="/running/">Overview</a><br />
	<a href="/running/managing-cf/quota-plans.html">
		Creating and Modifying Quota Plans</a><br />
    <a href="/running/managing-cf/logging.html">Logging</a><br />
    <a href="/running/troubleshooting.html">
		Troubleshooting Cloud Foundry</a><br />
    <a href="/running/troubleshooting/troubleshooting-apps.html">
		Troubleshooting Applications</a><br />
    <a href="/running/troubleshooting/troubleshooting-warden-services.html">
		Troubleshooting Wardenized Services</a></p>
  <hr />
  <p>
    Administer Cloud Foundry<br />
    <a href="/adminguide/cli-user-management.html">
	cf CLI User Management</a><br />
    <a href="/adminguide/uaa-user-management.html">
	UAA User Management</a><br />
    <a href="/adminguide/buildpacks.html">
	Adding Buildpacks to Cloud Foundry</a><br />
    <a href="/adminguide/app-sec-groups.html">
	Application Security Groups</a><br />
  </p>
</div>
</div>
<div>
  <h2>Reference</h2>
  <p><a href="/concepts/glossary.html">Cloud Foundry Glossary</a></p>
  For a look at what is planned, see the
  [community wiki](https://github.com/cloudfoundry-community/cf-docs-contrib/wiki).
</div>

