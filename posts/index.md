---
layout: page
title: My Skills
excerpt: "A List of Skills"
comments: false
---

<style>
    /* Added custom styles for the image container */
    .service-container {
        display: flex;
        flex-wrap: wrap;
        justify-content: space-around;
    }

    /* Adjusted the width to accommodate three images in a row */
    .service-item {
        flex: 0 0 calc(33.33% - 20px);
        margin: 10px;
        text-align: center;
    }
</style>

<div class="container">
    <div class="row text-center service-container">

        <!-- AWS -->
        <div class="col-lg-4 col-md-6 col-sm-12 mb-4 service-item" onclick="toggleDescription('aws')">
            <img class="rounded-circle img-fluid" src="../assets/img/svc/aws.jpg" alt="Service Icon" style="width: 100px; height: 100px;">
            <h4 class="service-heading"><p>AWS</p></h4>
            <p>Click to view details</p>
            <div class="text-muted">
                <p id="awsDescription" class="hidden-description" style="display: none;">
                    AWS 아키텍처를 구성한 뒤, 직접 생성하고 연결할 수 있습니다. 보안을 위해 VPC 및 서브넷을 생성하고, 역할과 정책을 구성할 수 있습니다.
                </p>
            </div>
        </div>

        <!-- Java Script -->
        <div class="col-lg-4 col-md-6 col-sm-12 mb-4 service-item" onclick="toggleDescription('js')">
            <!-- ... (similar structure for other skills) -->
        </div>

        <!-- Kubernetes -->
        <div class="col-lg-4 col-md-6 col-sm-12 mb-4 service-item" onclick="toggleDescription('kubernetes')">
            <!-- ... -->
        </div>

        <!-- Linux -->
        <div class="col-lg-4 col-md-6 col-sm-12 mb-4 service-item" onclick="toggleDescription('linux')">
            <!-- ... -->
        </div>

        <!-- Terraform -->
        <div class="col-lg-4 col-md-6 col-sm-12 mb-4 service-item" onclick="toggleDescription('terraform')">
            <!-- ... -->
        </div>

        <!-- Visual Studio Code -->
        <div class="col-lg-4 col-md-6 col-sm-12 mb-4 service-item" onclick="toggleDescription('vscode')">
            <!-- ... -->
        </div>

    </div>
</div>

<script>
    function toggleDescription(service) {
        var description = document.getElementById(service + 'Description');
        if (description.style.display === 'none' || description.style.display === '') {
            description.style.display = 'block';
        } else {
            description.style.display = 'none';
        }
    }
</script>
