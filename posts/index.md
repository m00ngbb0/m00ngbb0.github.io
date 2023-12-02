---
layout: page
title: My Skills
excerpt: "A List of Skills"
comments: false
---

<div class="row">
    <div class="col-lg-12 text-center">
        <h3 class="section-subheading text-muted">저는 이것을 주로 사용합니다.</h3>
    </div>
</div>

<div class="row text-center">
    <!-- AWS -->
    <div class="col-md-4 mb-4" onclick="toggleDescription('aws')">
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
    <div class="col-md-4 mb-4" onclick="toggleDescription('js')">
        <img class="rounded-circle img-fluid" src="../assets/img/svc/js.jpg" alt="Service Icon" style="width: 100px; height: 100px;">
        <h4 class="service-heading"><p>Java Script</p></h4>
        <p>Click to view details</p>
        <div class="text-muted">
            <p id="jsDescription" class="hidden-description" style="display: none;">
                Java Script를 이용하여 웹사이트의 동적인 요소를 구현해 본 경험이 있습니다. Node.js를 사용하여 서버 사이드 애플리케이션을 구현해 본 경험이 있습니다.
            </p>
        </div>
    </div>

    <!-- Kubernetes -->
    <div class="col-md-4 mb-4" onclick="toggleDescription('kubernetes')">
        <img class="rounded-circle img-fluid" src="../assets/img/svc/ks.jpg" alt="Service Icon" style="width: 100px; height: 100px;">
        <h4 class="service-heading"><p>Kubernetes</p></h4>
        <p>Click to view details</p>
        <div class="text-muted">
            <p id="kubernetesDescription" class="hidden-description" style="display: none;">
                Kubernetes 클러스터를 구성하고, 파드, 서비스, 볼륨 등의 리소스를 관리할 수 있습니다. Docker 컨테이너 기술을 이용하는 애플리케이션을 구성하고 배포해 본 경험이 있습니다.
            </p>
        </div>
    </div>
</div>

<div class="row text-center">
    <!-- Linux -->
    <div class="col-md-4 mb-4" onclick="toggleDescription('linux')">
        <img class="rounded-circle img-fluid" src="../assets/img/svc/li.jpg" alt="Service Icon" style="width: 100px; height: 100px;">
        <h4 class="service-heading"><p>Linux</p></h4>
        <p>Click to view details</p>
        <div class="text-muted">
            <p id="linuxDescription" class="hidden-description" style="display: none;">
                Linux 커맨드 라인 인터페이스(CLI)를 이용하여 파일 및 디렉토리 작업, 패키지 설치, 서비스 제어 등을 수행할 수 있습니다. Linux에서 사용되는 Ubuntu를 설치하고 구성하는 방법을 알고 있습니다.
            </p>
        </div>
    </div>

    <!-- Terraform -->
    <div class="col-md-4 mb-4" onclick="toggleDescription('terraform')">
        <img class="rounded-circle img-fluid" src="../assets/img/svc/te.jpg" alt="Service Icon" style="width: 100px; height: 100px;">
        <h4 class="service-heading"><p>Terraform</p></h4>
        <p>Click to view details</p>
        <div class="text-muted">
            <p id="terraformDescription" class="hidden-description" style="display: none;">
                Terraform을 이용하여 AWS의 클라우드 서비스를 구성하고 프로비저닝할 수 있습니다. Terraform을 사용하여 IaC(Infrastructure as Code)를 구현하고, 인프라스럭처의 버전 관리 및 변경 이력 추적을 할 수 있습니다.
            </p>
        </div>
    </div>

    <!-- Visual Studio Code -->
    <div class="col-md-4 mb-4" onclick="toggleDescription('vscode')">
        <img class="rounded-circle img-fluid" src="../assets/img/svc/vs.jpg" alt="Service Icon" style="width: 100px; height: 100px;">
        <h4 class="service-heading"><p>Visual Studio Code</p></h4>
        <p>Click to view details</p>
        <div class="text-muted">
            <p id="vscodeDescription" class="hidden-description" style="display: none;">
                VS Code를 사용하여 코드 편집, 버전 관리, 플러그인 관리 등 다양한 작업을 수행할 수 있습니다. VS Code의 단축키와 명령어를 이용하여 더욱 효율적으로 코드 작업을 수행할 수 있습니다.
            </p>
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
