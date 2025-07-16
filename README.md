
terraform init
terraform plan -out=plan.tfplan
terraform show -json plan.tfplan > plan.json
python3 demo.py
